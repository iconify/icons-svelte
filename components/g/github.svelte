<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/q/qv7h2s_bd.css';
import '../../css/f/frnub0hjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="d2kvgvbvc"><path class="qv7h2s_bd"/><path class="frnub0hjz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:github" {...props}></Icon>
