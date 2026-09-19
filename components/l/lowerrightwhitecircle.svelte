<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etftr2brq.css';
import '../../css/i/i4pcs4-lg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="etftr2brq"/><circle class="i4pcs4-lg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:lowerrightwhitecircle" {...props}></Icon>
