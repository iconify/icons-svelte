<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2q10-yfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="k2q10-yfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-windows-filled" {...props}></Icon>
