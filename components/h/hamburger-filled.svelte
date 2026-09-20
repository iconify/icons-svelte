<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zngysg_hj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zngysg_hj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:hamburger-filled" {...props}></Icon>
