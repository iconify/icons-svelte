<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/c/ca3ngwbkk.css';
import '../../css/f/f2l9xt51j.css';
import '../../css/l/l99bg1nyp.css';
import '../../css/u/ug3d5wb8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="ca3ngwbkk wm-shadow"/><path class="f2l9xt51j wm-shadow"/><path class="l99bg1nyp"/><path class="ug3d5wb8c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:burger" {...props}></Icon>
