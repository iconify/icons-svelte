<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xck5rbc3z.css';
import '../../css/j/jl5ph-bdp.css';
import '../../css/c/cequp8b6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="xck5rbc3z"><path class="jl5ph-bdp"/><path class="cequp8b6z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:notepad-text" {...props}></Icon>
