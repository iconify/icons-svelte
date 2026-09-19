<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b-5zx-b9n.css';
import '../../css/l/l437umi1x.css';
import '../../css/a/a2r_75btl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="b-5zx-b9n"/><path class="l437umi1x"/><path class="a2r_75btl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:box-close" {...props}></Icon>
