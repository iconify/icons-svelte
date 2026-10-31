<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkv48acbf.css';
import '../../css/f/fefa1ib-u.css';
import '../../css/c/cw36_6mco.css';
import '../../css/h/h13-u3bnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="fefa1ib-u wm-k"/><path class="cw36_6mco wm-a"/><path class="h13-u3bnw wm-deco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-kawaii:chart-spline" {...props}></Icon>
