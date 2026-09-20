<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2ip-cb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="j2ip-cb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:fan" {...props}></Icon>
