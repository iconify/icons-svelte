<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqbelnb7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iqbelnb7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:network-ups-tools-light" {...props}></Icon>
