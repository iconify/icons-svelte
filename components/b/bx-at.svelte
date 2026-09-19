<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykf1wub3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykf1wub3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-at" {...props}></Icon>
