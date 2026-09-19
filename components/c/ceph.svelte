<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3l3y1bpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="m3l3y1bpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:ceph" {...props}></Icon>
