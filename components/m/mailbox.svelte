<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h1qujs_dy.css';
import '../../css/g/gsq-yacdn.css';
import '../../css/g/gg3eanund.css';
import '../../css/m/mtktsu4wn.css';
import '../../css/f/fye000bgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="h1qujs_dy"/><path clip-rule="evenodd" class="gsq-yacdn"/><path class="gg3eanund"/><path class="mtktsu4wn"/><path class="fye000bgg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:mailbox" {...props}></Icon>
