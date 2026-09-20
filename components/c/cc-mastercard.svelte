<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x324subsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x324subsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:cc-mastercard" {...props}></Icon>
