<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-alhcbxd.css';
import '../../css/i/ifa3sbbtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j-alhcbxd"/><path class="ifa3sbbtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:memory-chip-20" {...props}></Icon>
