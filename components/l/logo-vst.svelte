<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/h/hygzc7f2b.css';
import '../../css/d/dxvxrfbem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="n1lsf0bnc"><path class="hygzc7f2b"/><path class="dxvxrfbem"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:logo-vst" {...props}></Icon>
