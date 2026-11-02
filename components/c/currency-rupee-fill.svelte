<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpw3vkzya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dpw3vkzya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-rupee-fill" {...props}></Icon>
