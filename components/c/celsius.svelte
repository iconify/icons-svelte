<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp7ke-b2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zp7ke-b2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:celsius" {...props}></Icon>
