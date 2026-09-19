<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/ygxrgebqz.css';
import '../../css/y/yts6p_bsd.css';
import '../../css/b/b8-7g1_4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ygxrgebqz"/><ellipse class="yts6p_bsd"/><path class="b8-7g1_4e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:coin" {...props}></Icon>
