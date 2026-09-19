<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-dcs0bkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="e-dcs0bkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:crosshairs-1" {...props}></Icon>
