<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzn6gmbtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzn6gmbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:font-serif" {...props}></Icon>
