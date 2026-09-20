<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcv7r2bxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcv7r2bxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:pencil-ai-2-fill" {...props}></Icon>
