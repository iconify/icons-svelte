<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e01znbbdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e01znbbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:cursor-arrow-fill-16" {...props}></Icon>
