<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbih7kn9p.css';
import '../../css/l/lsg5j7ibl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pbih7kn9p"/><path class="lsg5j7ibl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:cloud-circle-outline" {...props}></Icon>
