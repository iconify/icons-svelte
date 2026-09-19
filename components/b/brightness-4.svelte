<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbmop0bub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":488,"height":496};
const content = `<path class="wbmop0bub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:brightness-4" {...props}></Icon>
