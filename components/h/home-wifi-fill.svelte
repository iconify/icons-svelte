<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl7klpbfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tl7klpbfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:home-wifi-fill" {...props}></Icon>
