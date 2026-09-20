<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydh0_hbhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydh0_hbhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:grill" {...props}></Icon>
