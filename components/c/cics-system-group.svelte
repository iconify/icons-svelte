<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhhkwqoof.css';
import '../../css/w/wclgmvb9s.css';
import '../../css/d/d_tdrgg1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yhhkwqoof"/><path class="wclgmvb9s"/><path class="d_tdrgg1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cics-system-group" {...props}></Icon>
