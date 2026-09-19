<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl54b9bcm.css';
import '../../css/h/h45xcdbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fl54b9bcm"/><path class="h45xcdbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:calendar-check" {...props}></Icon>
