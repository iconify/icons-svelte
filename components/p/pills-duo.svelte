<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qdee2rzxp.css';
import '../../css/y/yzq0i0b1u.css';
import '../../css/s/sd69p3baz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="qdee2rzxp"/><path class="yzq0i0b1u"/><path class="sd69p3baz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:pills-duo" {...props}></Icon>
