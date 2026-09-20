<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3xdyvzhs.css';
import '../../css/m/m--ipvi-j.css';
import '../../css/g/gch5xlsgc.css';
import '../../css/b/b1__pbbes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m3xdyvzhs"/><path class="m--ipvi-j"/><path class="gch5xlsgc"/><path class="b1__pbbes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:beephotos" {...props}></Icon>
