<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf2m3cbtu.css';
import '../../css/q/q36jvnbvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yf2m3cbtu"/><path class="q36jvnbvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:kanban-20" {...props}></Icon>
