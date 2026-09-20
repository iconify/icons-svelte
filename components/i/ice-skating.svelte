<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-yg5n77r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="c-yg5n77r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:ice-skating" {...props}></Icon>
