<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x17iilibs.css';
import '../../css/c/c3k235b9x.css';
import '../../css/l/ligjalpvc.css';
import '../../css/v/vj9qhvlqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":250,"height":250};
const content = `<g class="x17iilibs"><path class="c3k235b9x"/><path class="ligjalpvc"/><path class="vj9qhvlqx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:remotion" {...props}></Icon>
