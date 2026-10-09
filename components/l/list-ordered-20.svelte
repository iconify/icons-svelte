<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9b4hcc5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e9b4hcc5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:list-ordered-20" {...props}></Icon>
