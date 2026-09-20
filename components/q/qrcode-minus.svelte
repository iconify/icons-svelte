<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkui6ogfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pkui6ogfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:qrcode-minus" {...props}></Icon>
