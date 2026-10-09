<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv6cn3b_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iv6cn3b_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-loss-48-bold" {...props}></Icon>
