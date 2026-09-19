<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh-18tbsw.css';
import '../../css/l/l-ba9qber.css';
import '../../css/d/dertp7bua.css';
import '../../css/g/gte4_q8cj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="jh-18tbsw"/><circle class="l-ba9qber"/><circle class="dertp7bua"/><path class="gte4_q8cj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:network-4" {...props}></Icon>
