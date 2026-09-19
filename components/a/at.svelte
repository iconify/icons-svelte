<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhvm94b4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fhvm94b4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:at" {...props}></Icon>
