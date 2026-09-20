<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxz--3bgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxz--3bgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:robot-2-line" {...props}></Icon>
