<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/azue8pydx.css';
import '../../css/l/lzncdxb9m.css';
import '../../css/f/fv2nt412f.css';
import '../../css/c/chplzrn1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="azue8pydx"/><path class="lzncdxb9m"/><path clip-rule="evenodd" class="fv2nt412f"/><path class="chplzrn1f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:material-three" {...props}></Icon>
