<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jpk7rbbjw.css';
import '../../css/e/efdwq-jsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<g class="ft5dv1b6b"><path class="jpk7rbbjw"/><path class="efdwq-jsz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gram" {...props}></Icon>
