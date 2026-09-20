<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgtdrqegm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgtdrqegm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:heart" {...props}></Icon>
