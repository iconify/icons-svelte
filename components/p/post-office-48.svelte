<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2pvmcr4g.css';
import '../../css/w/wl6oy3b4s.css';
import '../../css/d/dsq5v98-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m2pvmcr4g"/><path class="wl6oy3b4s"/><path class="dsq5v98-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:post-office-48" {...props}></Icon>
