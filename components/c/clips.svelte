<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-lju_hdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":417,"height":512};
const content = `<path class="a-lju_hdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:clips" {...props}></Icon>
