<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnqen6m1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="tnqen6m1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:location-arrow-outline" {...props}></Icon>
