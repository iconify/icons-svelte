<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbrj6dbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbrj6dbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:battery-line" {...props}></Icon>
