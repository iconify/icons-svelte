<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py5hh0bxr.css';
import '../../css/c/cu1d12b6p.css';
import '../../css/d/d5sbbcb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="py5hh0bxr"/><path class="cu1d12b6p"/><path class="d5sbbcb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:drawing-compass-48-bold" {...props}></Icon>
