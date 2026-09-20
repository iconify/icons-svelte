<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc4l1bimx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fc4l1bimx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:beets-dark" {...props}></Icon>
