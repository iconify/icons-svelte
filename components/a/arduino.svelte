<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7m6y0neb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t7m6y0neb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:arduino" {...props}></Icon>
