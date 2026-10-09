<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7t31nbyh.css';
import '../../css/m/ma29g-b3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i7t31nbyh"/><path class="ma29g-b3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:alert-20-bold" {...props}></Icon>
