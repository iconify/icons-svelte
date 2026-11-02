<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_8ww0brf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_8ww0brf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:candle-line" {...props}></Icon>
