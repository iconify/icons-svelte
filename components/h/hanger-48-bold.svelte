<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl9ati6se.css';
import '../../css/q/qfi21qbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jl9ati6se"/><path class="qfi21qbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hanger-48-bold" {...props}></Icon>
