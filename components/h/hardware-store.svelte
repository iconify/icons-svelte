<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t60evox7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="t60evox7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:hardware-store" {...props}></Icon>
