<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvxyzlvsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvxyzlvsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:clock-hour-10-filled" {...props}></Icon>
