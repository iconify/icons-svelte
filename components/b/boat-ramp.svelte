<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1br3obmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="n1br3obmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:boat-ramp" {...props}></Icon>
