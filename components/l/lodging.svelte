<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pt10m0b2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="pt10m0b2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:lodging" {...props}></Icon>
