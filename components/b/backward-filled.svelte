<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvqxqwb4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvqxqwb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:backward-filled" {...props}></Icon>
