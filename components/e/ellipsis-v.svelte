<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhcc7gpsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhcc7gpsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:ellipsis-v" {...props}></Icon>
