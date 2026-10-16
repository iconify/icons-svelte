<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iua8clh6p.css';
import '../../css/d/d8lollj3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iua8clh6p"/><path class="d8lollj3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carbon-tax-20-bold" {...props}></Icon>
