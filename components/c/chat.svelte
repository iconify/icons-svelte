<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/h/hmd6rr.css';
import '../../css/d/dxl7-q.css';
import '../../css/r/ruuz6o.css';
import '../../css/k/kivm5z.css';
import '../../css/s/so-from-70.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c hmd6rr"/><path class="a0m25c dxl7-q"/><path class="a0m25c ruuz6o"/><path class="a0m25c kivm5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:chat" {...props}></Icon>
