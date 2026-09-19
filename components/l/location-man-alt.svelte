<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1w22p8jq.css';
import '../../css/i/i388mubqy.css';
import '../../css/v/vc01epbab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="k1w22p8jq"/><path class="i388mubqy"/><circle class="vc01epbab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:location-man-alt" {...props}></Icon>
