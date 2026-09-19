<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xeap2lbts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xeap2lbts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:blackmediumsquare" {...props}></Icon>
