<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl2-kobue.css';
import '../../css/n/n93i43b7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jl2-kobue"/><path class="n93i43b7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:dotnetcore" {...props}></Icon>
