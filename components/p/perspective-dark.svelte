<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/usngqit7o.css';
import '../../css/k/kyjj1r1_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<g class="ft5dv1b6b"><path class="usngqit7o"/><path clip-rule="evenodd" class="kyjj1r1_l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:perspective-dark" {...props}></Icon>
