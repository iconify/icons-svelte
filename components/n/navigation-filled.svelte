<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfo4sqbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfo4sqbsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:navigation-filled" {...props}></Icon>
