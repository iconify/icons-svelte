<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxhz2_bsp.css';
import '../../css/w/wbz7ex9hn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxhz2_bsp"/><path class="wbz7ex9hn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bsw" {...props}></Icon>
