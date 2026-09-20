<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fx54jrb3b.css';
import '../../css/v/v4we60c2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":400,"height":400};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGtGRvv7uU)"><path class="fx54jrb3b"/></g><defs><clipPath id="SVGtGRvv7uU"><path class="v4we60c2i"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:elementor" {...props}></Icon>
