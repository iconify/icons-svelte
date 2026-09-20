<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ziq5wspty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ziq5wspty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hexagram" {...props}></Icon>
