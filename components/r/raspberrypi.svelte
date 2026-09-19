<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr3x-ib6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="dr3x-ib6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:raspberrypi" {...props}></Icon>
