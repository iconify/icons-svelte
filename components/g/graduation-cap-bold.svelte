<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/imaghvb2r.css';
import '../../css/w/wjk4-1mdx.css';
import '../../css/w/wyd9l79cu.css';
import '../../css/u/u3lsibblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="imaghvb2r"/><path class="wjk4-1mdx"/><path class="wyd9l79cu"/><path class="u3lsibblk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:graduation-cap-bold" {...props}></Icon>
