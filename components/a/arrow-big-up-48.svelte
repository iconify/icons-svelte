<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms6ew-l8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ms6ew-l8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-big-up-48" {...props}></Icon>
