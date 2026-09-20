<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gisz0600z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gisz0600z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:calendar-search3-filled" {...props}></Icon>
