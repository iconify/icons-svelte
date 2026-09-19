<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc22_bkfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":384};
const content = `<path class="xc22_bkfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:phone-end" {...props}></Icon>
