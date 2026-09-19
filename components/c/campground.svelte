<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py7p6nbby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="py7p6nbby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:campground" {...props}></Icon>
