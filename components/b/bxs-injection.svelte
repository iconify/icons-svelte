<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwmhwbcdr.css';
import '../../css/e/erph9zbjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwmhwbcdr"/><path class="erph9zbjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-injection" {...props}></Icon>
