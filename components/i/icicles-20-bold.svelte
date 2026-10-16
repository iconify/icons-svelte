<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3tyo9b4u.css';
import '../../css/o/ocquk-bcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e3tyo9b4u"/><path class="ocquk-bcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:icicles-20-bold" {...props}></Icon>
