<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crn9mubct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crn9mubct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-bomb" {...props}></Icon>
