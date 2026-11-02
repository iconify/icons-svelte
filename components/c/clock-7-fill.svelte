<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bppp0b1tb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bppp0b1tb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clock-7-fill" {...props}></Icon>
