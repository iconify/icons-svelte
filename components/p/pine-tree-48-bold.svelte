<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1vqxhqob.css';
import '../../css/c/c07srb4ol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f1vqxhqob"/><path class="c07srb4ol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pine-tree-48-bold" {...props}></Icon>
