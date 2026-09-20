<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqdg-r_-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rqdg-r_-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:grin-hearts-solid" {...props}></Icon>
