<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oly6fdb5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="oly6fdb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:italic" {...props}></Icon>
