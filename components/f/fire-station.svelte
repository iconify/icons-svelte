<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vot-hdb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="vot-hdb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:fire-station" {...props}></Icon>
