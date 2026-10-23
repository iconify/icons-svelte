<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp6mnbcdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yp6mnbcdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:pilcrow-right" {...props}></Icon>
