<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs-iz4qkj.css';
import '../../css/o/oqygufz8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qs-iz4qkj"/><path class="oqygufz8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:linkedin" {...props}></Icon>
