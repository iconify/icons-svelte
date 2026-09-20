<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi018xb3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="pi018xb3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gatsby" {...props}></Icon>
