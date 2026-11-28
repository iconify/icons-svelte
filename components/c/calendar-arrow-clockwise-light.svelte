<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-k1sjv1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="e-k1sjv1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:calendar-arrow-clockwise-light" {...props}></Icon>
