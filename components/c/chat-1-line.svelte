<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzed_32fq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzed_32fq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chat-1-line" {...props}></Icon>
