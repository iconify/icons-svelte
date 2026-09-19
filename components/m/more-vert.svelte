<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz7kfkb-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":88,"height":384};
const content = `<path class="pz7kfkb-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:more-vert" {...props}></Icon>
