<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0wqr5p5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i0wqr5p5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:haus-light" {...props}></Icon>
