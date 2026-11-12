<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyqt350ra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tyqt350ra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:geopulse-dark" {...props}></Icon>
