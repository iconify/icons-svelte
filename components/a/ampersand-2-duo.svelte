<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsm13zbds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="lsm13zbds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:ampersand-2-duo" {...props}></Icon>
