<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi-09xbts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fi-09xbts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:people-sleeping-in-bunkbeds-in-eaved-gabled-building" {...props}></Icon>
