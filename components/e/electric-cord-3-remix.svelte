<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1g_tcb2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s1g_tcb2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:electric-cord-3-remix" {...props}></Icon>
