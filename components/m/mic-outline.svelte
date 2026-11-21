<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9irpyjfv.css';
import '../../css/o/opkm_bb8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a9irpyjfv"/><path class="opkm_bb8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:mic-outline" {...props}></Icon>
