<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa9uucfpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pa9uucfpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:arrow-circle-right" {...props}></Icon>
