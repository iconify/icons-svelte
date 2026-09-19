<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkq1b1b5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xkq1b1b5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:face-meh-blank" {...props}></Icon>
