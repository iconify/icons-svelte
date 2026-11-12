<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdzw2qd4h.css';
import '../../css/y/yrbx-abvk.css';
import '../../css/t/tqets1biq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gdzw2qd4h"/><path class="yrbx-abvk"/><path class="tqets1biq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-powerpoint-dark" {...props}></Icon>
