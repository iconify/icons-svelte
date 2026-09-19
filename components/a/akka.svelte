<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chchrgbld.css';
import '../../css/h/hockizoar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="chchrgbld"/><path class="hockizoar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:akka" {...props}></Icon>
