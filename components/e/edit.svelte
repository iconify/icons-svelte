<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/d/ddx_6x.css';
import '../../css/d/d-uxzh.css';
import '../../css/i/idmydr.css';
import '../../css/s/so-to-0.css';
import '../../css/s/so-from-20.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c ddx_6x"/><path class="a0m25c d-uxzh"/><path class="a0m25c idmydr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:edit" {...props}></Icon>
