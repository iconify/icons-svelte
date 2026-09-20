<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyj6-4hbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="xyj6-4hbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:receive" {...props}></Icon>
