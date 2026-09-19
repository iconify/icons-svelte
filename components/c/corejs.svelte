<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4lt0ubcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="l4lt0ubcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:corejs" {...props}></Icon>
