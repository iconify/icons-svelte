<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur6p-47xu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ur6p-47xu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:luggage-14" {...props}></Icon>
