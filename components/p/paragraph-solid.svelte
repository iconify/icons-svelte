<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7yeswbyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s7yeswbyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:paragraph-solid" {...props}></Icon>
