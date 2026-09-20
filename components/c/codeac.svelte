<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glw37vbyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="glw37vbyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:codeac" {...props}></Icon>
