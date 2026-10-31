<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmoe46bpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rmoe46bpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:menu-alt-4-round" {...props}></Icon>
