<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/o/oi83abcqf.css';
import '../../css/w/wqmtzgbbi.css';
import '../../css/e/e-rh4-bqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="oi83abcqf"/><path class="wqmtzgbbi"/><path class="e-rh4-bqe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:instagram-logo-1" {...props}></Icon>
