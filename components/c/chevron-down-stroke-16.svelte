<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b86blp5az.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b86blp5az"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chevron-down-stroke-16" {...props}></Icon>
