<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk_xej3wr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tk_xej3wr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ai-agent-fill" {...props}></Icon>
