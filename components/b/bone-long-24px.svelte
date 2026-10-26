<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-yd735tb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-yd735tb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:bone-long-24px" {...props}></Icon>
