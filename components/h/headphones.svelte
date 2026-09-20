<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk8q9c5sb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vk8q9c5sb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:headphones" {...props}></Icon>
