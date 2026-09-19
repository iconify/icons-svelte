<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj84-dzad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hj84-dzad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:location-arrow" {...props}></Icon>
