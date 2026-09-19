<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8--75b_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p8--75b_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:mastercard" {...props}></Icon>
