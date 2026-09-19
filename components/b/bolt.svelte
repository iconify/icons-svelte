<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdk7pcc_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="xdk7pcc_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bolt" {...props}></Icon>
