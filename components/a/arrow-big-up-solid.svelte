<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx2_23bwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vx2_23bwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:arrow-big-up-solid" {...props}></Icon>
