<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq33__bcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xq33__bcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-eleven-filled" {...props}></Icon>
