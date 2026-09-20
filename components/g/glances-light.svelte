<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd2jl2a8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wd2jl2a8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:glances-light" {...props}></Icon>
