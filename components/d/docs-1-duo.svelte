<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pykjl9apf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="pykjl9apf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:docs-1-duo" {...props}></Icon>
