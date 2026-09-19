<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl00rlbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vl00rlbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:music-note" {...props}></Icon>
