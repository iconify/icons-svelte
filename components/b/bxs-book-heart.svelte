<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkp8b6b8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xkp8b6b8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-book-heart" {...props}></Icon>
