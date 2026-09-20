<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydd2y3hhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ydd2y3hhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:crane" {...props}></Icon>
