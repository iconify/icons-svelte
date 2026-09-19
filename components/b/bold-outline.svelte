<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8md_ek4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="a8md_ek4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bold-outline" {...props}></Icon>
