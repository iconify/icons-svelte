<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/x_dnedc0a.css';
import '../../css/z/zrzqsnbdu.css';
import '../../css/m/m0bfmobtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="x_dnedc0a"/><path class="zrzqsnbdu"/><path class="m0bfmobtd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:clock-fast" {...props}></Icon>
