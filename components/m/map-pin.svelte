<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2m49ccqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="k2m49ccqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:map-pin" {...props}></Icon>
