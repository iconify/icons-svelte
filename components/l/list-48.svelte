<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygo23sqro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ygo23sqro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:list-48" {...props}></Icon>
