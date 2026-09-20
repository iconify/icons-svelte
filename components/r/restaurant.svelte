<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5qio4snk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="c5qio4snk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:restaurant" {...props}></Icon>
