<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3x6jb9iv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3x6jb9iv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:ellipse" {...props}></Icon>
