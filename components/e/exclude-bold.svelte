<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bgxfxxbfa.css';
import '../../css/d/dlzwfk8ub.css';
import '../../css/y/y1wcivbjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="bgxfxxbfa"/><path class="dlzwfk8ub"/><path class="y1wcivbjr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:exclude-bold" {...props}></Icon>
