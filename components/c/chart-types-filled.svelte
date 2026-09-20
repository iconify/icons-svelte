<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxo32nbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="uxo32nbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:chart-types-filled" {...props}></Icon>
