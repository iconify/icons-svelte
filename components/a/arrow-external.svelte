<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/at-f_4bqo.css';
import '../../css/j/j7p-t2quf.css';
import '../../css/f/fvo3uwbbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="at-f_4bqo"/><path class="j7p-t2quf"/><path class="fvo3uwbbz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:arrow-external" {...props}></Icon>
