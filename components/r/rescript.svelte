<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhb8c01ug.css';
import '../../css/w/w03w98eed.css';
import '../../css/v/vzmjekozx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hhb8c01ug"><path class="w03w98eed"/><path class="vzmjekozx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:rescript" {...props}></Icon>
