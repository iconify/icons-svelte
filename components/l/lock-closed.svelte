<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cts_fdbkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cts_fdbkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:lock-closed" {...props}></Icon>
