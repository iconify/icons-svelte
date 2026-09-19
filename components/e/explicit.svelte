<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkft393ug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="xkft393ug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:explicit" {...props}></Icon>
