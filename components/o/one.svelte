<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rznpa-uyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="rznpa-uyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:one" {...props}></Icon>
