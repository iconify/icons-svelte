<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvzui74pn.css';
import '../../css/u/uxmtnwu0t.css';
import '../../css/r/rb9owibwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dvzui74pn"/><path class="uxmtnwu0t"/><path class="rb9owibwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:loan-48-bold" {...props}></Icon>
