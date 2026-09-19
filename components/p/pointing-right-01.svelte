<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy20y2b_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sy20y2b_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pointing-right-01" {...props}></Icon>
