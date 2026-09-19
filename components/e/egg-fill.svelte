<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef_45p5km.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ef_45p5km"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:egg-fill" {...props}></Icon>
