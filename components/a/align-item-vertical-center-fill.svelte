<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq16mac-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pq16mac-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:align-item-vertical-center-fill" {...props}></Icon>
