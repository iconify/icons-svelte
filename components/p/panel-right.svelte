<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctrlet0df.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u_4xy8b8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<defs><path id="SVGXWFExeZn" class="ctrlet0df"/></defs><mask id="SVGqCX3GcaG" class="cuyn6tgcc"><use href="#SVGXWFExeZn"/></mask><g class="cuyn6tgcc"><use href="#SVGXWFExeZn"/><path mask="url(#SVGqCX3GcaG)" class="u_4xy8b8b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:panel-right" {...props}></Icon>
