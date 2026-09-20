<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o3ondoz6y.css';
import '../../css/z/zigw2kbcr.css';
import '../../css/v/vn3oyvbre.css';
import '../../css/o/o_0di8bvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="o3ondoz6y"/><path class="zigw2kbcr"/><circle class="vn3oyvbre"/><circle class="o_0di8bvq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:face-smile2" {...props}></Icon>
