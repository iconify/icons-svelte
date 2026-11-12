<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i--9t9r5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i--9t9r5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:linkwarden-light" {...props}></Icon>
