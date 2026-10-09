<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gghdvqo-j.css';
import '../../css/r/rqsrs2a_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gghdvqo-j"/><path class="rqsrs2a_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:audit-20-bold" {...props}></Icon>
