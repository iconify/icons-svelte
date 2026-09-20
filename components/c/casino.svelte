<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe8xt8c8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="fe8xt8c8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:casino" {...props}></Icon>
