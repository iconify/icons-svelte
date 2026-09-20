<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_llhuate.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z_llhuate"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:flip-horizontal-outline" {...props}></Icon>
