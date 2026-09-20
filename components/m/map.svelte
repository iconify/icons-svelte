<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc46zh7yn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sc46zh7yn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:map" {...props}></Icon>
