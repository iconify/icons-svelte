<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3tnoebhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":432};
const content = `<path class="n3tnoebhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:hourglass-alt" {...props}></Icon>
