<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv8sn4hcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hv8sn4hcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pi-hole-dark" {...props}></Icon>
