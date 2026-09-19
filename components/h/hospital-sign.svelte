<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn80c9n7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="nn80c9n7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hospital-sign" {...props}></Icon>
