<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5-wb9brz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m5-wb9brz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ferris-wheel-line" {...props}></Icon>
