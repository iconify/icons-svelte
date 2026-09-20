<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k--vkf9cl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k--vkf9cl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:building-fill" {...props}></Icon>
