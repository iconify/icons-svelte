<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co7oz4bhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="co7oz4bhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:message-circle-warning-filled" {...props}></Icon>
