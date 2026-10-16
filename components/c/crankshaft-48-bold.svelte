<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4nxybn5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w4nxybn5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crankshaft-48-bold" {...props}></Icon>
