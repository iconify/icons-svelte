<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpx3f3tcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gpx3f3tcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:jet" {...props}></Icon>
