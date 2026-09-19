<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdf80gtnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="zdf80gtnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:dollar-sign-duo" {...props}></Icon>
