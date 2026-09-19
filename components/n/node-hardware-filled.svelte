<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr-yfwb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lr-yfwb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:node-hardware-filled" {...props}></Icon>
