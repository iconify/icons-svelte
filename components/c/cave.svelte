<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwu55hr8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nwu55hr8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cave" {...props}></Icon>
