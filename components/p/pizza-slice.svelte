<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhck25btm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mhck25btm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:pizza-slice" {...props}></Icon>
