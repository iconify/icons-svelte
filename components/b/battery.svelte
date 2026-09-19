<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-cl05b2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":216,"height":432};
const content = `<path class="u-cl05b2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:battery" {...props}></Icon>
