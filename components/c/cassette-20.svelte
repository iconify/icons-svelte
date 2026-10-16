<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4l8cxbpg.css';
import '../../css/j/j6agt1nji.css';
import '../../css/x/x07i0sb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t4l8cxbpg"/><path class="j6agt1nji"/><path class="x07i0sb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cassette-20" {...props}></Icon>
