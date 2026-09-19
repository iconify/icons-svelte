<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs254vjqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="hs254vjqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:money-bill-trend-up" {...props}></Icon>
