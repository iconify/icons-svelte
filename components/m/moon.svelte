<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjgy8sb3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="jjgy8sb3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:moon" {...props}></Icon>
