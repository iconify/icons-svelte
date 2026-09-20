<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iiomx44uq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iiomx44uq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:framework-dark" {...props}></Icon>
