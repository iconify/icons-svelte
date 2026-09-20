<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0l2ahb_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s0l2ahb_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:heart" {...props}></Icon>
