<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl8ogjbin.css';
import '../../css/v/vbn5-wb4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1440,"height":810};
const content = `<defs><clipPath id="SVG6nCoMc7C"><path class="zl8ogjbin"/></clipPath></defs><g clip-path="url(#SVG6nCoMc7C)"><path class="vbn5-wb4u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:farmsent" {...props}></Icon>
