<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isc5-ebbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="isc5-ebbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:chevron-circle-left-solid" {...props}></Icon>
