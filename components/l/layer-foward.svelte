<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kupkbm0sm.css';
import '../../css/s/sgs5pgp6p.css';
import '../../css/i/ihy1gojel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="kupkbm0sm"/><path clip-rule="evenodd" class="sgs5pgp6p"/><path class="ihy1gojel"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:layer-foward" {...props}></Icon>
