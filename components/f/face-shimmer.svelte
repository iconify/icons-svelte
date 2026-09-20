<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq07mm04a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mq07mm04a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:face-shimmer" {...props}></Icon>
