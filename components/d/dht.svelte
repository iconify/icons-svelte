<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w85oa8b0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w85oa8b0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:dht" {...props}></Icon>
