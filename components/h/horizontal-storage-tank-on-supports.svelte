<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f38hztbpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f38hztbpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:horizontal-storage-tank-on-supports" {...props}></Icon>
