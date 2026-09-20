<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oii_trd6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="oii_trd6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:postal-code" {...props}></Icon>
