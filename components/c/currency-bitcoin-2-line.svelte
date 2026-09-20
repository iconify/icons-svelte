<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2x_3ebpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2x_3ebpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-bitcoin-2-line" {...props}></Icon>
