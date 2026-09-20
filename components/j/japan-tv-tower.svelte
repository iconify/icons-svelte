<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfcmr664f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rfcmr664f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:japan-tv-tower" {...props}></Icon>
