<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxng7opnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wxng7opnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:living-room" {...props}></Icon>
