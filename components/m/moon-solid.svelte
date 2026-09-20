<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdqd-gbiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tdqd-gbiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:moon-solid" {...props}></Icon>
