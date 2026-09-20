<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfuueobig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfuueobig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mailbox-line" {...props}></Icon>
