<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jux0sgb4d.css';
import '../../css/i/i3h_fy-ls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jux0sgb4d"/><path class="i3h_fy-ls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:power-button" {...props}></Icon>
