<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha8_tdyso.css';
import '../../css/r/r0ghz7b6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ha8_tdyso"/><path class="r0ghz7b6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:mapleleaf" {...props}></Icon>
