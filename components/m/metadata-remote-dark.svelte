<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmu_k5bmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vmu_k5bmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:metadata-remote-dark" {...props}></Icon>
