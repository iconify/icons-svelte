<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3lv1quhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3lv1quhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ice-cream" {...props}></Icon>
