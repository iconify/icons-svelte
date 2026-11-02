<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_4k2i3fx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_4k2i3fx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:nose-line" {...props}></Icon>
