<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgbmqc20c.css';
import '../../css/r/r-v6gebze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgbmqc20c"/><path class="r-v6gebze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:location-pin-filled" {...props}></Icon>
