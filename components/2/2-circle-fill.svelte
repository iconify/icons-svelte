<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt6747b6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yt6747b6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:2-circle-fill" {...props}></Icon>
