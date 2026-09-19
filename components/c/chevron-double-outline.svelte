<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1bbndrsh.css';
import '../../css/r/r2avjyb5n.css';
import '../../css/o/oosdw9lib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="j1bbndrsh"><path class="r2avjyb5n"/><path class="oosdw9lib"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:chevron-double-outline" {...props}></Icon>
