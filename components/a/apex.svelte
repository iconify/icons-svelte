<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2ruh8b8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="u2ruh8b8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:apex" {...props}></Icon>
