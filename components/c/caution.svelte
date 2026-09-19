<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/o799rcisc.css';
import '../../css/d/dufseh5oc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":35,"height":32};
const content = `<g class="cuyn6tgcc"><path class="o799rcisc"/><path class="dufseh5oc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:caution" {...props}></Icon>
