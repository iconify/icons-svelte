<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqenu4b1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqenu4b1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:map-setting-filled" {...props}></Icon>
