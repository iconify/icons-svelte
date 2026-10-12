<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl8wlmp8e.css';
import '../../css/s/sflf_gome.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jl8wlmp8e"/><path class="sflf_gome"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:eye-strike-fill-20" {...props}></Icon>
