<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rjvum3bja.css';
import '../../css/r/rs8zu5blz.css';
import '../../css/c/czg5n3blq.css';
import '../../css/n/nmfipnb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="rjvum3bja"/><path clip-rule="evenodd" class="rs8zu5blz"/><path class="czg5n3blq"/><path clip-rule="evenodd" class="nmfipnb4g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:credit-card-outline" {...props}></Icon>
