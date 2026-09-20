<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzu25db3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzu25db3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:candles-line" {...props}></Icon>
