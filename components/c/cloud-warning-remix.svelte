<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbw8hbcnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vbw8hbcnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cloud-warning-remix" {...props}></Icon>
