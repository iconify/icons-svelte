<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvsbw4j5h.css';
import '../../css/c/cuyn6tgcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<defs><path id="SVGtFnCvbNU" class="vvsbw4j5h"/></defs><use href="#SVGtFnCvbNU" class="cuyn6tgcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:pie-chart" {...props}></Icon>
