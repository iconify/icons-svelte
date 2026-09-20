<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9cfkmbsk.css';
import '../../css/h/h695rk-bi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a9cfkmbsk"/><path class="h695rk-bi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:exchange-bitcoin-fill" {...props}></Icon>
