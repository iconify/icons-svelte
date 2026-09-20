<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edex25bdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="edex25bdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:bulb-filled" {...props}></Icon>
