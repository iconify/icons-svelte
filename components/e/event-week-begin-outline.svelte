<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drw4bvb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drw4bvb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:event-week-begin-outline" {...props}></Icon>
