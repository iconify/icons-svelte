<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm-v76dnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="sm-v76dnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:crop-3-2" {...props}></Icon>
