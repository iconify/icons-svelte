<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wl90geboo.css';
import '../../css/h/h695rk-bi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wl90geboo"/><path class="h695rk-bi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:exchange-cny-fill" {...props}></Icon>
