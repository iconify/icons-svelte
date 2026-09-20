<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx-2lwb9f.css';
import '../../css/a/atjk8mbde.css';
import '../../css/a/a9o5t_b5e.css';
import '../../css/p/pnfsjvx9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="bx-2lwb9f"/><g class="atjk8mbde"><path class="a9o5t_b5e"/><path class="pnfsjvx9q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:geogebra" {...props}></Icon>
