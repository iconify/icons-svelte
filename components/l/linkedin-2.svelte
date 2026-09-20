<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2pskb3hb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2pskb3hb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:linkedin-2" {...props}></Icon>
