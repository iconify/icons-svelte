<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnaf7qbot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="xnaf7qbot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:funeral-home" {...props}></Icon>
