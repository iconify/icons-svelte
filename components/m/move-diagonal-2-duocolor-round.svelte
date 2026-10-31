<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knisc_b1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knisc_b1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:move-diagonal-2-duocolor-round" {...props}></Icon>
