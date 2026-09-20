<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egnuz7xuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egnuz7xuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:candles-fill" {...props}></Icon>
