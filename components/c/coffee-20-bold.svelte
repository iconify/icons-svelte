<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsm6o3u7u.css';
import '../../css/u/uw4qzh0ap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lsm6o3u7u"/><path class="uw4qzh0ap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:coffee-20-bold" {...props}></Icon>
