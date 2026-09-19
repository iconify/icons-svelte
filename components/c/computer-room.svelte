<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2ta8jbyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e2ta8jbyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:computer-room" {...props}></Icon>
