<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rggfaqb6e.css';
import '../../css/l/l6wq4teao.css';
import '../../css/p/p7ix2ibsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="rggfaqb6e"><path class="l6wq4teao"/><path clip-rule="evenodd" class="p7ix2ibsl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:radar-two" {...props}></Icon>
