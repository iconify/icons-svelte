<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l59rj_b_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="l59rj_b_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:chairlift" {...props}></Icon>
