<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqao4p0gj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="vqao4p0gj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:dynamodb" {...props}></Icon>
