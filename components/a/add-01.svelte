<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytb8_xbkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytb8_xbkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:add-01" {...props}></Icon>
