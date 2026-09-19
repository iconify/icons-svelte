<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ts_9zc_xm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ts_9zc_xm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:rooms-driveway" {...props}></Icon>
