<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk_1_t7py.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vk_1_t7py"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:debug" {...props}></Icon>
