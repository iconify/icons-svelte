<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox2vwfbfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="ox2vwfbfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:grin-hearts" {...props}></Icon>
