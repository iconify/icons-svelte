<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb7_vlbxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="rb7_vlbxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:fullscreen" {...props}></Icon>
