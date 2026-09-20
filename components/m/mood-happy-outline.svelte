<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjugbmb8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qjugbmb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:mood-happy-outline" {...props}></Icon>
