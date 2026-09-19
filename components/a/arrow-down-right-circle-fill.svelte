<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f86d5ub3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f86d5ub3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-down-right-circle-fill" {...props}></Icon>
