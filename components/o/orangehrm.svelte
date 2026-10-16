<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8r--tbbc.css';
import '../../css/n/ni0ydvbwi.css';
import '../../css/m/mswb4uy9b.css';
import '../../css/t/tm4h_tz1k.css';
import '../../css/v/v135c1b7p.css';
import '../../css/u/u8ws8ibhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":750.11,"height":189.77};
const content = `<path class="b8r--tbbc"/><path class="ni0ydvbwi"/><path class="mswb4uy9b"/><path class="tm4h_tz1k"/><path class="v135c1b7p"/><path class="u8ws8ibhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:orangehrm" {...props}></Icon>
