<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_nd-1x5c.css';
import '../../css/y/ybmr-8bzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e_nd-1x5c"/><path class="ybmr-8bzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:connector-chademo-20" {...props}></Icon>
