<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p45gor59d.css';
import '../../css/d/doyyo9bqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p45gor59d"/><path class="doyyo9bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:network-3-reference" {...props}></Icon>
