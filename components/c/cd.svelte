<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bs8xkbbwh.css';
import '../../css/b/b5eoc9f6b.css';
import '../../css/f/fh0rozb0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":301,"height":225};
const content = `<g class="ft5dv1b6b"><path class="bs8xkbbwh"/><path class="b5eoc9f6b"/><path class="fh0rozb0g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cif:cd" {...props}></Icon>
