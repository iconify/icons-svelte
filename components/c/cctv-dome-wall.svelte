<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th6wg-bkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="th6wg-bkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:cctv-dome-wall" {...props}></Icon>
