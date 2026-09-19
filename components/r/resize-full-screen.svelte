<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gef9zeb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gef9zeb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:resize-full-screen" {...props}></Icon>
