<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqccm1buv.css';
import '../../css/h/hw4m2zm2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qqccm1buv"/><path class="hw4m2zm2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:fridge" {...props}></Icon>
