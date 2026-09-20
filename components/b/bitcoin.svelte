<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8vlxmbmn.css';
import '../../css/g/g-4pifb7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<path class="l8vlxmbmn"/><path clip-rule="evenodd" class="g-4pifb7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:bitcoin" {...props}></Icon>
