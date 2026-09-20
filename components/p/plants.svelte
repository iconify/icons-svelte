<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je9q0nbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="je9q0nbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:plants" {...props}></Icon>
