<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl3l9ccqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vl3l9ccqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:calendar-key" {...props}></Icon>
