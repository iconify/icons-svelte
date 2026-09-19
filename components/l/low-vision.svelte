<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjzeqy2ft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1664};
const content = `<path class="yjzeqy2ft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:low-vision" {...props}></Icon>
