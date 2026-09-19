<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bcazt4rfm.css';
import '../../css/b/bnjmyndfa.css';
import '../../css/d/dipsfvb4p.css';
import '../../css/d/d-h_ycbnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="bcazt4rfm"/><path class="bnjmyndfa"/><path clip-rule="evenodd" class="dipsfvb4p"/><path class="d-h_ycbnd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:campfire-outline" {...props}></Icon>
