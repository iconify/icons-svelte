<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q039x4b1z.css';
import '../../css/v/v32r9rbgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q039x4b1z"/><path class="v32r9rbgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:image" {...props}></Icon>
