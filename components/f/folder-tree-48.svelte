<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1p_9z-6l.css';
import '../../css/z/z3rbxgblu.css';
import '../../css/j/j80farb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h1p_9z-6l"/><path class="z3rbxgblu"/><path class="j80farb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-tree-48" {...props}></Icon>
