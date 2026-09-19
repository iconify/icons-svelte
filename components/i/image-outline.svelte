<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/f/f-rc7hbej.css';
import '../../css/m/mal9x4b_u.css';
import '../../css/v/vjupb11qn.css';
import '../../css/a/a30pbeb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="f-rc7hbej"/><path class="mal9x4b_u"/><path class="vjupb11qn"/><path class="a30pbeb1v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:image-outline" {...props}></Icon>
