<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv4krgb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iv4krgb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-add" {...props}></Icon>
