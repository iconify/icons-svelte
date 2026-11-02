<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hodbwfbjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hodbwfbjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:grid-3x3-fill" {...props}></Icon>
