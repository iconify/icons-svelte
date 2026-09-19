<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll1hldbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ll1hldbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:ecere" {...props}></Icon>
