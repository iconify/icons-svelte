<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-b0mlbul.css';
import '../../css/i/i5s91diaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q-b0mlbul"/><path class="i5s91diaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charger-dual-20-bold" {...props}></Icon>
