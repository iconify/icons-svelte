<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk1jq-b8e.css';
import '../../css/x/x4l5l87lu.css';
import '../../css/c/crda83b7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yk1jq-b8e"/><path class="x4l5l87lu"/><path class="crda83b7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:goal-48-bold" {...props}></Icon>
