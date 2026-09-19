<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/j/jehkic28y.css';
import '../../css/f/fszl4kf6j.css';
import '../../css/h/hugh8jbpc.css';
import '../../css/c/c0vuimrvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="jehkic28y"/><path class="fszl4kf6j"/><path class="hugh8jbpc"/><path class="c0vuimrvq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:garage-outline" {...props}></Icon>
