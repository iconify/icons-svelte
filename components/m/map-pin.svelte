<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjgcx4_5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wjgcx4_5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:map-pin" {...props}></Icon>
