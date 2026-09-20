<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmcfcsbbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xmcfcsbbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:barcode" {...props}></Icon>
