<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5teh5yky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="y5teh5yky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:data-transfer-download" {...props}></Icon>
