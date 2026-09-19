<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msel8rbya.css';
import '../../css/z/zt3trxb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="msel8rbya"/><path class="zt3trxb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:email" {...props}></Icon>
