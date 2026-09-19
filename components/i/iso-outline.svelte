<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qiv05cixr.css';
import '../../css/w/w1voi0bfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qiv05cixr"/><path class="w1voi0bfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:iso-outline" {...props}></Icon>
