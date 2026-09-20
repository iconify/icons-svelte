<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-h1us7qj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j-h1us7qj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:bottom-align-outline" {...props}></Icon>
