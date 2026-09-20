<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp87u6c8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zp87u6c8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ray-start-arrow" {...props}></Icon>
