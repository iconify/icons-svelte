<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od-ttjbcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="od-ttjbcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-battery-dead" {...props}></Icon>
