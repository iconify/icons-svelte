<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/deu9usb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="deu9usb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:apple-news" {...props}></Icon>
