<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9t99pbvc.css';
import '../../css/f/flil27bwc.css';
import '../../css/t/tb6-f1eyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l9t99pbvc"/><path class="flil27bwc"/><path class="tb6-f1eyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:beach-hut-20-bold" {...props}></Icon>
