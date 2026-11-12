<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl2f_dlbg.css';
import '../../css/e/erolj7bif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jl2f_dlbg"/><path class="erolj7bif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ironcalc-light" {...props}></Icon>
