<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz5bqhgic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vz5bqhgic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:immich-power-tools-dark" {...props}></Icon>
