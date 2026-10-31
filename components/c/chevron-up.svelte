<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/s/s2l7nm5ll.css';
import '../../css/h/hijd9prfl.css';
import '../../css/m/mo-o3pb_t.css';
import '../../css/r/runsd0bzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="s2l7nm5ll wm-shadow"/><path class="hijd9prfl wm-shadow"/><path class="mo-o3pb_t"/><path class="runsd0bzl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:chevron-up" {...props}></Icon>
