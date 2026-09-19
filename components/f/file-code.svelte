<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/b/b6mrdacjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><polyline points="2.75 7.75 2.75 1.75 8.25 1.75 13.25 6.75 13.25 14.25 11.25 14.25"/><polyline points="7.75 2.25 7.75 7.25 12.8 7.25"/><path class="b6mrdacjb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:file-code" {...props}></Icon>
