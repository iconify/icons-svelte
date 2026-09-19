<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxe2qqrqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wxe2qqrqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:add-01" {...props}></Icon>
