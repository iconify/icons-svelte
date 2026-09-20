<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro28oxbjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ro28oxbjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-down-line" {...props}></Icon>
