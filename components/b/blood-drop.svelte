<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i9s6hlb1c.css';
import '../../css/p/p8r6vku4o.css';
import '../../css/b/bvyi81cxr.css';
import '../../css/m/mpmo64bka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i9s6hlb1c"/><path class="p8r6vku4o"/><path class="bvyi81cxr"/><path class="mpmo64bka"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber-color:blood-drop" {...props}></Icon>
