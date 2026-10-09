<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq3i9_lhj.css';
import '../../css/y/ydkyucbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lq3i9_lhj"/><path class="ydkyucbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:api-20" {...props}></Icon>
