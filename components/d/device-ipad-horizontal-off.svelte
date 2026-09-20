<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo2s3nbzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xo2s3nbzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-ipad-horizontal-off" {...props}></Icon>
