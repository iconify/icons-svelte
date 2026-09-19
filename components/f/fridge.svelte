<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sstq2fy_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sstq2fy_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:fridge" {...props}></Icon>
