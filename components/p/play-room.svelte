<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb5_-u6mi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tb5_-u6mi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:play-room" {...props}></Icon>
