<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-9iiqe2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="c-9iiqe2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:nine" {...props}></Icon>
