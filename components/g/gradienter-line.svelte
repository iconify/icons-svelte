<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv4va0_8o.css';
import '../../css/n/nl5ridb9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fv4va0_8o"/><path class="nl5ridb9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:gradienter-line" {...props}></Icon>
