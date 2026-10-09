<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4vli7ncu.css';
import '../../css/y/yrudknc6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j4vli7ncu"/><path class="yrudknc6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crosshair-48-bold" {...props}></Icon>
