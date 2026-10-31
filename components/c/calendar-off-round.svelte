<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv07bsafv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wv07bsafv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:calendar-off-round" {...props}></Icon>
