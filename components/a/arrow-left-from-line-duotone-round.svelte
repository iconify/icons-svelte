<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgh_cmt6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgh_cmt6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-left-from-line-duotone-round" {...props}></Icon>
