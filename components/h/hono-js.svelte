<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjg40r0in.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjg40r0in"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:hono-js" {...props}></Icon>
