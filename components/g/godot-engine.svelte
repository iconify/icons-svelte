<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuz0ehvlf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tuz0ehvlf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:godot-engine" {...props}></Icon>
