<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rirux2j4y.css';
import '../../css/a/acwmw9bjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rirux2j4y"/><path class="acwmw9bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cut-out" {...props}></Icon>
