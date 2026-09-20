<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2f32u7hy.css';
import '../../css/p/pfssstxrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="r2f32u7hy"/><path class="pfssstxrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:mobile-phone" {...props}></Icon>
