<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmsa-7c1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rmsa-7c1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:paragraph-right" {...props}></Icon>
