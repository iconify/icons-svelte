<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkxvsbbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="xkxvsbbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:label" {...props}></Icon>
