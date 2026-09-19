<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smvtmjbjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="smvtmjbjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:clear-formatting" {...props}></Icon>
