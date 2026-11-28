<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8wlneb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="j8wlneb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:magnifying-glass-x-fill" {...props}></Icon>
