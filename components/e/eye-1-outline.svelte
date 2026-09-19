<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1bbndrsh.css';
import '../../css/c/c6y1s8ces.css';
import '../../css/o/o4x2yi1vx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="j1bbndrsh"><path clip-rule="evenodd" class="c6y1s8ces"/><path class="o4x2yi1vx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:eye-1-outline" {...props}></Icon>
