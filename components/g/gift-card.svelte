<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/ae3506h7l.css';
import '../../css/l/lgfkdnbmi.css';
import '../../css/y/yduk_kccx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><rect class="ae3506h7l"/><path class="lgfkdnbmi"/><path class="yduk_kccx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:gift-card" {...props}></Icon>
