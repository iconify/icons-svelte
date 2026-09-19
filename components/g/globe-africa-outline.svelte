<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0t_jjb1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="r0t_jjb1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:globe-africa-outline" {...props}></Icon>
