<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb8s_pcfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sb8s_pcfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hook0-light" {...props}></Icon>
