<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji1cc1dkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ji1cc1dkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:candlestick" {...props}></Icon>
