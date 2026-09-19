<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtrk6zyad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wtrk6zyad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:regionalindicatorg" {...props}></Icon>
