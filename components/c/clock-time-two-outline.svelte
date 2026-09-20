<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdbw9nx4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdbw9nx4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clock-time-two-outline" {...props}></Icon>
