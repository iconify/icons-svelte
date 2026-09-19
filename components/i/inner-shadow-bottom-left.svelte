<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gopnm44um.css';
import '../../css/i/i--wlebtf.css';
import '../../css/k/kvmwukb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="gopnm44um"><path clip-rule="evenodd" class="i--wlebtf"/><path class="kvmwukb9h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:inner-shadow-bottom-left" {...props}></Icon>
