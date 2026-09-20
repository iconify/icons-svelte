<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sys-ifbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sys-ifbsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:bra-sports" {...props}></Icon>
