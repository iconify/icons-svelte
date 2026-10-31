<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d87dqc3wl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d87dqc3wl wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-boy-gloss" {...props}></Icon>
