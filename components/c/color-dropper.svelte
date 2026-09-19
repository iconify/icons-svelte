<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3x57yb9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d3x57yb9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:color-dropper" {...props}></Icon>
