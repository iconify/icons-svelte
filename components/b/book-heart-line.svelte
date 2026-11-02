<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us95y-boj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="us95y-boj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-heart-line" {...props}></Icon>
