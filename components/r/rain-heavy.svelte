<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mit5f8bas.css';
import '../../css/e/ek_6wsbdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mit5f8bas"/><path class="ek_6wsbdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:rain-heavy" {...props}></Icon>
