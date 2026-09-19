<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws1-s1f7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ws1-s1f7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:chair" {...props}></Icon>
