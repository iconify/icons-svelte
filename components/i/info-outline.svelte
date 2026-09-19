<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytwuz5yos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="ytwuz5yos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:info-outline" {...props}></Icon>
