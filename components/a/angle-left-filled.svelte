<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn-4l5o8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sn-4l5o8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:angle-left-filled" {...props}></Icon>
