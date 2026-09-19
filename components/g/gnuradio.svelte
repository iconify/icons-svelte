<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjaxq7boy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="gjaxq7boy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:gnuradio" {...props}></Icon>
