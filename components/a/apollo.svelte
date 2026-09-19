<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulra56alq.css';
import '../../css/x/xrqhfhb1a.css';
import '../../css/a/axioowbpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="ulra56alq"><path class="xrqhfhb1a"/><path class="axioowbpp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:apollo" {...props}></Icon>
