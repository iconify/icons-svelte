<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg-0_nb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wg-0_nb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:arrow-thick-from-bottom" {...props}></Icon>
