<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3tyy5-9p.css';
import '../../css/u/u6c4ubc7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t3tyy5-9p"/><path class="u6c4ubc7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:penguin-20-bold" {...props}></Icon>
