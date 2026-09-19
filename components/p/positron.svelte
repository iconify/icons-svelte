<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da-peabtg.css';
import '../../css/u/udo33x03z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<rect class="da-peabtg"/><path class="udo33x03z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:positron" {...props}></Icon>
