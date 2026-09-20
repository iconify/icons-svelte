<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo828zbqm.css';
import '../../css/d/d2kvgvbvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":375,"height":375};
const content = `<defs><path id="SVGsLty1dHV" class="zo828zbqm"/></defs><use href="#SVGsLty1dHV" class="d2kvgvbvc"/><use href="#SVGsLty1dHV" class="d2kvgvbvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:glincker-light" {...props}></Icon>
