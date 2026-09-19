<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knsyygmgu.css';
import '../../css/a/a6hum9hrz.css';
import '../../css/d/doyyo9bqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="knsyygmgu"/><path class="a6hum9hrz"/><path class="doyyo9bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:network-3" {...props}></Icon>
