<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rza_6mg2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rza_6mg2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:object-ungroup" {...props}></Icon>
