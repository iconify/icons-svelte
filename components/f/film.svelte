<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkh5wzb4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bkh5wzb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:film" {...props}></Icon>
