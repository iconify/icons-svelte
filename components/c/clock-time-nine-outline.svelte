<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpq7__boy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xpq7__boy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clock-time-nine-outline" {...props}></Icon>
