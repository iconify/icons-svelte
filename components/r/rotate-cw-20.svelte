<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht0kv9akh.css';
import '../../css/x/xl70_ubev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ht0kv9akh"/><path class="xl70_ubev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rotate-cw-20" {...props}></Icon>
