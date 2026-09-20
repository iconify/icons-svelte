<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqf0ry-2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqf0ry-2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:home-smile-line" {...props}></Icon>
