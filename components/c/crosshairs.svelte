<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk7sdpbyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="tk7sdpbyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:crosshairs" {...props}></Icon>
