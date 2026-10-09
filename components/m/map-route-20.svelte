<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovcrl6b2y.css';
import '../../css/a/a9_-6201d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ovcrl6b2y"/><path class="a9_-6201d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:map-route-20" {...props}></Icon>
