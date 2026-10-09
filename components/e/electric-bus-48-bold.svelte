<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5pdqgm9m.css';
import '../../css/c/ctik4kd5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f5pdqgm9m"/><path class="ctik4kd5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-bus-48-bold" {...props}></Icon>
