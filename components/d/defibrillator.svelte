<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3f894b8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q3f894b8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:defibrillator" {...props}></Icon>
