<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/d/dreuuh66c.css';
import '../../css/c/c7l0uwbsa.css';
import '../../css/d/dfm8uyd9a.css';
import '../../css/k/khrsx4-mv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="dreuuh66c"/><path class="c7l0uwbsa"/><path class="dfm8uyd9a"/><path class="khrsx4-mv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:globe-oceania-outline" {...props}></Icon>
