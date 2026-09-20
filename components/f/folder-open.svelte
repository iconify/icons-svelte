<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3ayd58ao.css';
import '../../css/k/ki6lx60di.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m3ayd58ao"/><path class="ki6lx60di"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:folder-open" {...props}></Icon>
