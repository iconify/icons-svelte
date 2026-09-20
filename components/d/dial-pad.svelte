<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9_vk-szz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l9_vk-szz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:dial-pad" {...props}></Icon>
