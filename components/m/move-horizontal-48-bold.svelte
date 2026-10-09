<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz8zsd5cc.css';
import '../../css/w/wived3hxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wz8zsd5cc"/><path class="wived3hxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:move-horizontal-48-bold" {...props}></Icon>
