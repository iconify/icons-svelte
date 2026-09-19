<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl_di5buv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="gl_di5buv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:check-double" {...props}></Icon>
