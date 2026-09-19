<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1bbndrsh.css';
import '../../css/u/ullp8vaok.css';
import '../../css/n/nx2c618gt.css';
import '../../css/d/douhlrken.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="j1bbndrsh"><path class="ullp8vaok"/><path class="nx2c618gt"/><path class="douhlrken"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:docs-outline" {...props}></Icon>
