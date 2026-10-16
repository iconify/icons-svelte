<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrb0n9bgf.css';
import '../../css/r/rzr08ebez.css';
import '../../css/j/jzzafn9vl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yrb0n9bgf"/><path class="rzr08ebez"/><path class="jzzafn9vl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:org-chart-48" {...props}></Icon>
