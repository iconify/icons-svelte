<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr-s6ybza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dr-s6ybza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circleright" {...props}></Icon>
