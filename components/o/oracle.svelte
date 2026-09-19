<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxt7nkbyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="vxt7nkbyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:oracle" {...props}></Icon>
