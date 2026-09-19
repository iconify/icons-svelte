<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgno_hn4s.css';
import '../../css/h/hgpzimtyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tgno_hn4s"/><path class="hgpzimtyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-candlestick" {...props}></Icon>
