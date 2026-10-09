<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo1l9hn0b.css';
import '../../css/i/i9xwo4sma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uo1l9hn0b"/><path class="i9xwo4sma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ladder-20" {...props}></Icon>
