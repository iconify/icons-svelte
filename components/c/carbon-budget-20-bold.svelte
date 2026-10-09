<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_ezx1bzs.css';
import '../../css/f/f46-hd4vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u_ezx1bzs"/><path class="f46-hd4vn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carbon-budget-20-bold" {...props}></Icon>
