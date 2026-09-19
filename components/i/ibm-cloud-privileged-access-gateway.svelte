<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usifnk4ig.css';
import '../../css/b/bv734nb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="usifnk4ig"/><path class="bv734nb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-privileged-access-gateway" {...props}></Icon>
