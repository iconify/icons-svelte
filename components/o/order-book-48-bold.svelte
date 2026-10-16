<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4mctibtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q4mctibtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:order-book-48-bold" {...props}></Icon>
