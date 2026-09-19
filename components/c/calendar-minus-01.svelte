<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv4m4mbnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xv4m4mbnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:calendar-minus-01" {...props}></Icon>
