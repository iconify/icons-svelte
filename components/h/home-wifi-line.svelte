<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yeoay0l6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yeoay0l6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:home-wifi-line" {...props}></Icon>
