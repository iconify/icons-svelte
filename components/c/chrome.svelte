<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px4e0xvna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="px4e0xvna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:chrome" {...props}></Icon>
