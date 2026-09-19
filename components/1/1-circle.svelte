<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp_tly-yv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vp_tly-yv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:1-circle" {...props}></Icon>
