<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1v2rsb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="o1v2rsb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:foursquare" {...props}></Icon>
