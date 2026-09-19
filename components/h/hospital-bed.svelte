<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfcmd9bxj.css';
import '../../css/g/gv22t7b6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dfcmd9bxj"/><path class="gv22t7b6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:hospital-bed" {...props}></Icon>
