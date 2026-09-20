<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od72l_b0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="od72l_b0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ellipsis-horizontal-circle-outline" {...props}></Icon>
