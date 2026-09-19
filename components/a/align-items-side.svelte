<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v01kf7p0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="v01kf7p0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:align-items-side" {...props}></Icon>
