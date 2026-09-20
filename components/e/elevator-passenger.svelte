<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq_3l-byg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iq_3l-byg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:elevator-passenger" {...props}></Icon>
