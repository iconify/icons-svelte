<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/j/jcxlm2b2l.css';
import '../../css/k/kvhr17bhl.css';
import '../../css/f/ftoe0cc3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="jcxlm2b2l"/><path class="kvhr17bhl"/><path class="ftoe0cc3c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:file-txt" {...props}></Icon>
