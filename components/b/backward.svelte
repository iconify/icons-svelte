<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3t02abaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a3t02abaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:backward" {...props}></Icon>
