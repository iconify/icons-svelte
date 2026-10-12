<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw5-nd-eu.css';
import '../../css/p/pegc-mbyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uw5-nd-eu"/><path class="pegc-mbyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pill-bottle-20-bold" {...props}></Icon>
