<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id95kqb4w.css';
import '../../css/a/a8ioorcne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="id95kqb4w"/><path class="a8ioorcne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gas-flare-20-bold" {...props}></Icon>
