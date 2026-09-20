<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/roek0__-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="roek0__-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:id-card" {...props}></Icon>
