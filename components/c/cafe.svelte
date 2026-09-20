<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlls81mbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="wlls81mbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:cafe" {...props}></Icon>
