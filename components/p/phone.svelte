<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/f/fxn87v4vx.css';
import '../../css/t/tz1j7bbth.css';
import '../../css/o/ovnv7qxik.css';
import '../../css/o/oivujhbti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="fxn87v4vx wm-shadow"/><path class="tz1j7bbth wm-shadow"/><path class="ovnv7qxik"/><path class="oivujhbti"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:phone" {...props}></Icon>
