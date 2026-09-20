<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3ed_tbcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d3ed_tbcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:restaurant" {...props}></Icon>
