<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wglews2po.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":448};
const content = `<path class="wglews2po"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:minus" {...props}></Icon>
