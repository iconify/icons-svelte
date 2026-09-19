<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5h3u4r9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="t5h3u4r9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:phone-call-transfer-only-stroke-12" {...props}></Icon>
