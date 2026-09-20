<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4a50lb_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4a50lb_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:rickshaw-electric" {...props}></Icon>
