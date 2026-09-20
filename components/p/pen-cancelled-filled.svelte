<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m057asb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="m057asb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:pen-cancelled-filled" {...props}></Icon>
