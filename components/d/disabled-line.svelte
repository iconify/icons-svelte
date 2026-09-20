<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwbocdjcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwbocdjcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:disabled-line" {...props}></Icon>
