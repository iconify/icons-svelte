<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vui4akb2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1728,"height":1536};
const content = `<path class="vui4akb2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:header" {...props}></Icon>
