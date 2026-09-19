<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/e6vv4yb6l.css';
import '../../css/w/w0m1pxb-u.css';
import '../../css/c/cimrciz-d.css';
import '../../css/y/y6ia5_idg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="e6vv4yb6l"/><path class="w0m1pxb-u"/><path class="cimrciz-d"/><path class="y6ia5_idg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:penguin" {...props}></Icon>
