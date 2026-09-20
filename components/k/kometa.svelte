<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlcb74b2i.css';
import '../../css/n/nlxy_dbcm.css';
import '../../css/m/moq4ohbbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xlcb74b2i"/><path class="nlxy_dbcm"/><path class="moq4ohbbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kometa" {...props}></Icon>
