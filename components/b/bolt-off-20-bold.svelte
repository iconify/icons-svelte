<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_dsj84zh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k_dsj84zh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bolt-off-20-bold" {...props}></Icon>
