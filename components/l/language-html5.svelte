<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjuv6rb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":360,"height":424};
const content = `<path class="kjuv6rb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:language-html5" {...props}></Icon>
