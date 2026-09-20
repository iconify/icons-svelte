<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4w44ubux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z4w44ubux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hourglass-solid" {...props}></Icon>
