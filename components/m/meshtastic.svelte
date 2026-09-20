<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqspvlzll.css';
import '../../css/s/sppq3wb1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gqspvlzll"/><path class="sppq3wb1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:meshtastic" {...props}></Icon>
