<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcii5u59n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcii5u59n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:coathanger-line" {...props}></Icon>
