<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx1ln9b3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qx1ln9b3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:romarr-light" {...props}></Icon>
