<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzq3j4dkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xzq3j4dkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:qrcode" {...props}></Icon>
