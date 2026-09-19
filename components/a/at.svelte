<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcu4mj0fs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mcu4mj0fs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:at" {...props}></Icon>
