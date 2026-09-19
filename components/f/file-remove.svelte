<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/ueln8bb9d.css';
import '../../css/j/jvkbjcbed.css';
import '../../css/g/g8wq2cb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ueln8bb9d"/><path class="jvkbjcbed"/><path class="g8wq2cb_f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:file-remove" {...props}></Icon>
