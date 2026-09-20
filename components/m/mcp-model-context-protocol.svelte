<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx5d-bc1s.css';
import '../../css/h/hd70nsb5x.css';
import '../../css/u/u2hv0zbsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nx5d-bc1s"><path class="hd70nsb5x"/><path class="u2hv0zbsy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mcp-model-context-protocol" {...props}></Icon>
