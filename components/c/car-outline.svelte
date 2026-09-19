<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/o/o1-5lfgdv.css';
import '../../css/q/qa_ur-bdp.css';
import '../../css/d/duhq62b0j.css';
import '../../css/m/ms7x4mb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="o1-5lfgdv"/><path class="qa_ur-bdp"/><path class="duhq62b0j"/><path class="ms7x4mb5m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:car-outline" {...props}></Icon>
