<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzjevtwje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mzjevtwje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:japan-well" {...props}></Icon>
