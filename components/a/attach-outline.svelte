<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuke3exgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zuke3exgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:attach-outline" {...props}></Icon>
