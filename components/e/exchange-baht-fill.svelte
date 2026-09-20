<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h695rk-bi.css';
import '../../css/y/yfbn82bpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h695rk-bi"/><path class="yfbn82bpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:exchange-baht-fill" {...props}></Icon>
