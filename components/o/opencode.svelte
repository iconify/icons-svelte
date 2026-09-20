<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0klx1dfy.css';
import '../../css/n/nr9_5n4qz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g transform="matrix(1.5 0 0 1.5 -23.858 -7.25)"><path class="x0klx1dfy"/><rect class="nr9_5n4qz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:opencode" {...props}></Icon>
