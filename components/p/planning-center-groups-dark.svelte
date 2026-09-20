<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvocr7pig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uvocr7pig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:planning-center-groups-dark" {...props}></Icon>
