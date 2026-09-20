<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffpnvgb5x.css';
import '../../css/k/kozsj6bao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ffpnvgb5x"/><path class="kozsj6bao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bagisto" {...props}></Icon>
