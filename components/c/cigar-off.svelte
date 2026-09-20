<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twmx-bcjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="twmx-bcjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cigar-off" {...props}></Icon>
