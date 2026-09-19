<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq9_gaclr.css';
import '../../css/e/e39ud6bwf.css';
import '../../css/k/kpnimx1ru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="dq9_gaclr"/><circle class="e39ud6bwf"/><circle class="kpnimx1ru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:overflow-menu-horizontal" {...props}></Icon>
