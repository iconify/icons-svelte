<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6aq-f6ay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="v6aq-f6ay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:activity-1" {...props}></Icon>
