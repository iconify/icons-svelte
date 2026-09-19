<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/o/ob04qqx7v.css';
import '../../css/n/n-omplb0y.css';
import '../../css/t/tennhxbfx.css';
import '../../css/n/nk5xvgx2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ob04qqx7v"/><path class="n-omplb0y"/><path class="tennhxbfx"/><path class="nk5xvgx2e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:bells" {...props}></Icon>
