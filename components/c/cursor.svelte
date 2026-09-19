<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1w6h6fuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u1w6h6fuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cursor" {...props}></Icon>
