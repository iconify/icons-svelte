<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl91ypb0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="nl91ypb0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:aerialway-11" {...props}></Icon>
