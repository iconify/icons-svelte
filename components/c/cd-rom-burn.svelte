<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1fmgbb9l.css';
import '../../css/j/jp007tmga.css';
import '../../css/y/yiyfahk2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c1fmgbb9l"/><path class="jp007tmga"/><path class="yiyfahk2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:cd-rom-burn" {...props}></Icon>
