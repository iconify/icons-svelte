<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/c/cdcw8t-og.css';
import '../../css/u/uqwcdyain.css';
import '../../css/j/j4eiq8x9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="cdcw8t-og"/><path class="uqwcdyain"/><path class="j4eiq8x9y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:add-subset" {...props}></Icon>
