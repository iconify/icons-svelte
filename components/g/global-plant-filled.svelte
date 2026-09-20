<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov260k97l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ov260k97l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:global-plant-filled" {...props}></Icon>
