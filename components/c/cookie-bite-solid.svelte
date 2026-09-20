<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9hum3b3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j9hum3b3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:cookie-bite-solid" {...props}></Icon>
