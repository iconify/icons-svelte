<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0f4p2b2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0f4p2b2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-up-right-small-fill-round" {...props}></Icon>
