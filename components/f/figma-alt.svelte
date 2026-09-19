<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6uj5ccbk.css';
import '../../css/v/vod56msze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6uj5ccbk"/><path class="vod56msze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:figma-alt" {...props}></Icon>
