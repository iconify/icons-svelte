<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssoyox_pc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ssoyox_pc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:battery-upright-empty" {...props}></Icon>
