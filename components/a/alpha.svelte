<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2ru7lcwo.css';
import '../../css/c/cuyn6tgcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGgxWCtbkt" class="g2ru7lcwo"/></defs><g class="cuyn6tgcc"><use href="#SVGgxWCtbkt"/><use href="#SVGgxWCtbkt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:alpha" {...props}></Icon>
