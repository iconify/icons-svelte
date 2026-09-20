<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/w/wddcw00vy.css';
import '../../css/x/x_zlyssnp.css';
import '../../css/t/t1ifqebhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="wddcw00vy"/><path class="x_zlyssnp"/><path class="t1ifqebhl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:controller-wireless-flat" {...props}></Icon>
