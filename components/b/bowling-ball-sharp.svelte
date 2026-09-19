<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl-5pmbed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jl-5pmbed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:bowling-ball-sharp" {...props}></Icon>
