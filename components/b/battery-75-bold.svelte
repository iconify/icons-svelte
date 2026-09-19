<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g85xu4buw.css';
import '../../css/f/fspb5xm8s.css';
import '../../css/l/lyvx4mbnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="g85xu4buw"/><path clip-rule="evenodd" class="fspb5xm8s"/><path class="lyvx4mbnc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:battery-75-bold" {...props}></Icon>
