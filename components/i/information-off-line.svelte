<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji7ws2beg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ji7ws2beg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:information-off-line" {...props}></Icon>
