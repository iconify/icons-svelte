<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0hkt3blc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u0hkt3blc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:calendar-heart" {...props}></Icon>
