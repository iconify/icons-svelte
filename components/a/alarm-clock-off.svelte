<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr_1r9b1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zr_1r9b1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:alarm-clock-off" {...props}></Icon>
