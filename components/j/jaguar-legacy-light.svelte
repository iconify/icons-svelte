<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmbmkcbbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1045.7,"height":85};
const content = `<path class="rmbmkcbbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:jaguar-legacy-light" {...props}></Icon>
