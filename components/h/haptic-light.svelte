<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij621sbil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ij621sbil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:haptic-light" {...props}></Icon>
