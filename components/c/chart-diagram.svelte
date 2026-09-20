<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwj65_bje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hwj65_bje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:chart-diagram" {...props}></Icon>
