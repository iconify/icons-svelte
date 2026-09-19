<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0_4_pb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i0_4_pb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:right-arrow-circle" {...props}></Icon>
