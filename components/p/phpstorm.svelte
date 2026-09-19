<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omc7subqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="omc7subqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:phpstorm" {...props}></Icon>
