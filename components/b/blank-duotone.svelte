<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlif8lbav.css';
import '../../css/f/f72_8xqoe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dlif8lbav"/><path class="f72_8xqoe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:blank-duotone" {...props}></Icon>
