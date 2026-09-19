<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi8211lux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1280};
const content = `<path class="pi8211lux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:bed" {...props}></Icon>
