<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eibrw93vl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eibrw93vl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:bowling" {...props}></Icon>
