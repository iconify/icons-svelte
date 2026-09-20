<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tare22g5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tare22g5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:menu-2-filled" {...props}></Icon>
