<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edg0qh-xn.css';
import '../../css/a/am03yhn7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="edg0qh-xn"/><path class="am03yhn7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:logo-rindo" {...props}></Icon>
