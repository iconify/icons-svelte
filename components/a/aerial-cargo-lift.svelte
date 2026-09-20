<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsi6l9whp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dsi6l9whp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:aerial-cargo-lift" {...props}></Icon>
