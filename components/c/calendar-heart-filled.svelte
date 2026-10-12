<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/teke80b1t.css';
import '../../css/s/srka-7bio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="teke80b1t"/><path class="srka-7bio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:calendar-heart-filled" {...props}></Icon>
