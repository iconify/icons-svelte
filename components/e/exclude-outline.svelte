<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne3sn9etj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ne3sn9etj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:exclude-outline" {...props}></Icon>
