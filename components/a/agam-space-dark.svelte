<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivutaubif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ivutaubif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:agam-space-dark" {...props}></Icon>
