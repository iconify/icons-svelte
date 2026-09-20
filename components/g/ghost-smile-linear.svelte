<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/w/wtzf3ijxf.css';
import '../../css/l/lhhyg8f6f.css';
import '../../css/s/sygjb24yx.css';
import '../../css/u/u7snxmbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="wtzf3ijxf"/><path class="lhhyg8f6f"/><path class="sygjb24yx"/><ellipse class="u7snxmbok"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ghost-smile-linear" {...props}></Icon>
