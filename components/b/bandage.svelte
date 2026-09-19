<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmh87urrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="bmh87urrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:bandage" {...props}></Icon>
