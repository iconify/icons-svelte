<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c0-ydxhpn.css';
import '../../css/i/ids849bmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="c0-ydxhpn"/><path class="ids849bmv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:postmark" {...props}></Icon>
