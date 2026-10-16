<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh4cf0bwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zh4cf0bwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:energy-mix-48" {...props}></Icon>
