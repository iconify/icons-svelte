<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/m/m04wr6bxv.css';
import '../../css/h/h3e1u3zis.css';
import '../../css/i/i3c4jibtn.css';
import '../../css/x/xcv5olncc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="m04wr6bxv"/><path class="h3e1u3zis"/><path class="i3c4jibtn"/><path class="xcv5olncc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:images-outline" {...props}></Icon>
