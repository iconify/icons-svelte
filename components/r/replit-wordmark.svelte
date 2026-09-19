<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8dwnefac.css';
import '../../css/v/vsi_9nbmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="d8dwnefac"/><path class="vsi_9nbmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:replit-wordmark" {...props}></Icon>
