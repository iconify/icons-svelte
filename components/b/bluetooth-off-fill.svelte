<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iumlklekx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iumlklekx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bluetooth-off-fill" {...props}></Icon>
