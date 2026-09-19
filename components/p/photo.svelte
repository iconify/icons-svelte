<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv7-5d-vk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1920,"height":1536};
const content = `<path class="qv7-5d-vk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:photo" {...props}></Icon>
