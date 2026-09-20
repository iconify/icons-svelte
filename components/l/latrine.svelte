<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-7-ds7vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="h-7-ds7vn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:latrine" {...props}></Icon>
