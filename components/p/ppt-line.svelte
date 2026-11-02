<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkdd5oshq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xkdd5oshq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ppt-line" {...props}></Icon>
