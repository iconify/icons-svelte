<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8ohewbfz.css';
import '../../css/c/cuyn6tgcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<defs><path id="SVG67go7b2R" class="s8ohewbfz"/></defs><g class="cuyn6tgcc"><use href="#SVG67go7b2R"/><use href="#SVG67go7b2R"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:apple" {...props}></Icon>
