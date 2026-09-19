<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri_vl6b7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ri_vl6b7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:justify-left" {...props}></Icon>
