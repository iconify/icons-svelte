<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kl2py6bsc.css';
import '../../css/e/e3wgdxbsg.css';
import '../../css/a/avjgxm8yh.css';
import '../../css/i/io3-j9bqa.css';
import '../../css/u/uu-ktdb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="kl2py6bsc"/><path class="e3wgdxbsg"/><path class="avjgxm8yh"/><path class="io3-j9bqa"/><path clip-rule="evenodd" class="uu-ktdb4s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:electric-scooter" {...props}></Icon>
