<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkfybybmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="rkfybybmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:cricket-11" {...props}></Icon>
