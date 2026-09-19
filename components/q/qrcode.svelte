<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_zkeqxre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="m_zkeqxre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:qrcode" {...props}></Icon>
