<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyp1fvbnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="oyp1fvbnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:bus-station" {...props}></Icon>
