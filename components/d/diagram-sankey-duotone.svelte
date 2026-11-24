<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/u6k2wgbfk.css';
import '../../css/l/lx2bb-bjy.css';
import '../../css/c/c8yfngb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u6k2wgbfk"/><path class="lx2bb-bjy"/><path class="c8yfngb2d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:diagram-sankey-duotone" {...props}></Icon>
