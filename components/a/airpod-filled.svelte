<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pumdp1b0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pumdp1b0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:airpod-filled" {...props}></Icon>
