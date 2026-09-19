<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se-dpyb_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":422,"height":717};
const content = `<path class="se-dpyb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:record" {...props}></Icon>
