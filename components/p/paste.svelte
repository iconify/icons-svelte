<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/o/o364n5cnh.css';
import '../../css/z/z3qqnubwe.css';
import '../../css/z/z1ppbibmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="o364n5cnh"/><path class="z3qqnubwe"/><path class="z1ppbibmx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:paste" {...props}></Icon>
