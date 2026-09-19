<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys4s-1b6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ys4s-1b6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:dollars" {...props}></Icon>
