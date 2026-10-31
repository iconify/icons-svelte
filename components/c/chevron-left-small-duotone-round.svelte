<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cset7o1an.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cset7o1an"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chevron-left-small-duotone-round" {...props}></Icon>
