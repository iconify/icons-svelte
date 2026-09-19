<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff-g0nb6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ff-g0nb6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:horizontal-left" {...props}></Icon>
