<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/c/c9ugt2t7n.css';
import '../../css/d/dbldgwbon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="c9ugt2t7n"/><path class="dbldgwbon"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:flip-1" {...props}></Icon>
