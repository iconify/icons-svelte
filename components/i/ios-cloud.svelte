<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtpg_fbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rtpg_fbri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-cloud" {...props}></Icon>
