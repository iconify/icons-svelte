<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbh2nacgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="hbh2nacgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:car-repair" {...props}></Icon>
