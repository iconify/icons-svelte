<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnvuc1b_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xnvuc1b_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:calendar-check2" {...props}></Icon>
