<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_ebc0dyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e_ebc0dyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-k3os-light" {...props}></Icon>
