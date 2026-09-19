<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjo891b4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yjo891b4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:monitor-two" {...props}></Icon>
