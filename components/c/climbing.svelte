<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy4y49t-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="uy4y49t-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:climbing" {...props}></Icon>
