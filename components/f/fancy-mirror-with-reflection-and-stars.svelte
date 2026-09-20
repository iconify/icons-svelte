<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc26uubtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uc26uubtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:fancy-mirror-with-reflection-and-stars" {...props}></Icon>
