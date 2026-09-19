<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3lsmi_yp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="y3lsmi_yp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:graduation-cap-outline" {...props}></Icon>
