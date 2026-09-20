<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzpx7ib5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pzpx7ib5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:device-view-hierarchical" {...props}></Icon>
