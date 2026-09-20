<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agh1_fbqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="agh1_fbqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:flashlight" {...props}></Icon>
