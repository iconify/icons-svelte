<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opo2qwbrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":432};
const content = `<path class="opo2qwbrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:notifications-off" {...props}></Icon>
