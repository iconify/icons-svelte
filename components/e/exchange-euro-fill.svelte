<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnkzy6zqq.css';
import '../../css/h/h695rk-bi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xnkzy6zqq"/><path class="h695rk-bi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:exchange-euro-fill" {...props}></Icon>
