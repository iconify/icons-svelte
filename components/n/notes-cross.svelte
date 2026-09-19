<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/v/v0ubzluje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><polyline points="8.25 14.25 2.75 14.25 2.75 1.75 13.25 1.75 13.25 8.25"/><path class="v0ubzluje"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:notes-cross" {...props}></Icon>
