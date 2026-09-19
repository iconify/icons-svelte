<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/touuu46vk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="touuu46vk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:frame" {...props}></Icon>
