<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk5gcgism.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vk5gcgism"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:ai-view" {...props}></Icon>
