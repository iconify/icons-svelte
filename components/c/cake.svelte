<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llfhb1b4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":472};
const content = `<path class="llfhb1b4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:cake" {...props}></Icon>
