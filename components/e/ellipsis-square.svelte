<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qvbcrdb1n.css';
import '../../css/z/z_cbqpboy.css';
import '../../css/h/hfo2n9z0l.css';
import '../../css/i/ideoyl8wk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><rect class="qvbcrdb1n"/><rect class="z_cbqpboy"/><rect class="hfo2n9z0l"/><rect class="ideoyl8wk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:ellipsis-square" {...props}></Icon>
