<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv-neabou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uv-neabou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:power-pole-delta" {...props}></Icon>
