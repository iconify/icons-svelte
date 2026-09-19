<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yms31tbmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="yms31tbmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:diamond-1" {...props}></Icon>
