<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnsha0bgv.css';
import '../../css/g/gol1xybds.css';
import '../../css/c/czudsiv_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lnsha0bgv"/><path class="gol1xybds"/><path class="czudsiv_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-wifi-feed" {...props}></Icon>
