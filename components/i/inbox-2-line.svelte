<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc7awjdrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rc7awjdrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:inbox-2-line" {...props}></Icon>
