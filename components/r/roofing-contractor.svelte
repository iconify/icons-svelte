<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yey0n_erf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="yey0n_erf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:roofing-contractor" {...props}></Icon>
