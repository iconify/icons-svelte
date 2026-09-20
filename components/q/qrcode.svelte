<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb3msxbjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="xb3msxbjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:qrcode" {...props}></Icon>
