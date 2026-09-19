<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu186ptsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lu186ptsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:question-mark" {...props}></Icon>
