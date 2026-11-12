<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snaubdbur.css';
import '../../css/k/k3cps1u4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="snaubdbur"/><path class="k3cps1u4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frankmd-dark" {...props}></Icon>
