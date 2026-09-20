<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgs60lb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hgs60lb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:linkedin-in" {...props}></Icon>
