<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncmcqbb8g.css';
import '../../css/i/ixw6t5b1b.css';
import '../../css/i/iu8op3j7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ncmcqbb8g"/><path class="ixw6t5b1b"/><path class="iu8op3j7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:energy-island-20" {...props}></Icon>
