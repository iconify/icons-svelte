<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/b/b8cd-f9hp.css';
import '../../css/r/r__fs9qdv.css';
import '../../css/d/d8x3xzbpj.css';
import '../../css/q/q5iwxve0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="b8cd-f9hp"/><path class="r__fs9qdv"/><path class="d8x3xzbpj"/><path class="q5iwxve0v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:branch-one" {...props}></Icon>
