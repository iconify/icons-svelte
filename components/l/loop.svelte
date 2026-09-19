<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rob-th-6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rob-th-6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:loop" {...props}></Icon>
