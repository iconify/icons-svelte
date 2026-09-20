<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6ybxsbrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6ybxsbrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:emoji-sticker-line" {...props}></Icon>
