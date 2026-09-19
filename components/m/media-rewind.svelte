<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><polygon points="7.75 3.75 7.75 12.25 1.75 8"/><polygon points="14.25 3.75 14.25 12.25 8.25 8"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:media-rewind" {...props}></Icon>
