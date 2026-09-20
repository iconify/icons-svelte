<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r00wx5u2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="r00wx5u2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:coin-filled" {...props}></Icon>
