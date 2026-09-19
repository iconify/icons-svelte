<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h53hy5b3q.css';
import '../../css/u/uuo7n4xwg.css';
import '../../css/n/nvwe-vbgl.css';
import '../../css/z/znan2-a4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="h53hy5b3q"/><path clip-rule="evenodd" class="uuo7n4xwg"/><path class="nvwe-vbgl"/><path clip-rule="evenodd" class="znan2-a4g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:camcorder-outline" {...props}></Icon>
