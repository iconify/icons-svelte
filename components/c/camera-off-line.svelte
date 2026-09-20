<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk4e1cchy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bk4e1cchy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:camera-off-line" {...props}></Icon>
