<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/d/d5ct4lbiy.css';
import '../../css/c/chf42nrhi.css';
import '../../css/y/yt88x7rlf.css';
import '../../css/x/xrspqab6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="d5ct4lbiy wm-shadow"/><path class="chf42nrhi wm-shadow"/><path class="yt88x7rlf"/><path class="xrspqab6t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:puzzle-piece" {...props}></Icon>
