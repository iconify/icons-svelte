<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd9e0jb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":448};
const content = `<path class="yd9e0jb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:moon" {...props}></Icon>
