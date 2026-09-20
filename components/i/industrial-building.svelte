<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbpfy51ay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kbpfy51ay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:industrial-building" {...props}></Icon>
