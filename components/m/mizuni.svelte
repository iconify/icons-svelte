<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt-ms-9kv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rt-ms-9kv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:mizuni" {...props}></Icon>
