<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnykq_boq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fnykq_boq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bug-pause-outline" {...props}></Icon>
