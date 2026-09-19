<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb3hhnbhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="lb3hhnbhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:foot-print" {...props}></Icon>
