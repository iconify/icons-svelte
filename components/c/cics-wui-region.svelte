<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i--l_kmzs.css';
import '../../css/j/jfuk8ubuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i--l_kmzs"/><path class="jfuk8ubuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cics-wui-region" {...props}></Icon>
