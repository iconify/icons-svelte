<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g95ndgrnv.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nkc4t8bfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<defs><path id="SVGpPI6ccam" class="g95ndgrnv"/></defs><mask id="SVGVEeC1biv" class="cuyn6tgcc"><use href="#SVGpPI6ccam"/></mask><g class="cuyn6tgcc"><use href="#SVGpPI6ccam"/><path mask="url(#SVGVEeC1biv)" class="nkc4t8bfx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:panel-bottom" {...props}></Icon>
