<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuu2q6-xf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="yuu2q6-xf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:bell" {...props}></Icon>
