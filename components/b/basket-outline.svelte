<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nd93jtbtx.css';
import '../../css/l/ls167c1hb.css';
import '../../css/d/dgi-9-bgx.css';
import '../../css/e/ejovddz-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="nd93jtbtx"/><path clip-rule="evenodd" class="ls167c1hb"/><path class="dgi-9-bgx"/><path clip-rule="evenodd" class="ejovddz-b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:basket-outline" {...props}></Icon>
