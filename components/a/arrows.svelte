<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo-wa019m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eo-wa019m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrows" {...props}></Icon>
