<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khre3_bur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="khre3_bur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:expeditedssl" {...props}></Icon>
