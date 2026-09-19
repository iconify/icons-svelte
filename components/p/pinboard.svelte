<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w494h98hw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":488};
const content = `<path class="w494h98hw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:pinboard" {...props}></Icon>
