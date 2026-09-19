<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7zlwfbdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<rect class="d7zlwfbdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:rectangle-bold" {...props}></Icon>
