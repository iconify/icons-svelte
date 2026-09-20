<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8pyz-fzo.css';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p_3zmsvya.css';
import '../../css/h/hstpbebig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGcPdOtdJO" class="t8pyz-fzo"/></defs><g class="ft5dv1b6b"><use href="#SVGcPdOtdJO"/><use href="#SVGcPdOtdJO" class="p_3zmsvya"/><path class="hstpbebig"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:grid-add" {...props}></Icon>
