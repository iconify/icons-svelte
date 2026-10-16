<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbdwctb6r.css';
import '../../css/w/w2y26nmkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cbdwctb6r"/><path class="w2y26nmkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:disconnector-20-bold" {...props}></Icon>
