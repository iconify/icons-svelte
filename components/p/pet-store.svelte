<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jem06bpnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="jem06bpnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:pet-store" {...props}></Icon>
