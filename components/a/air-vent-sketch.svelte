<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pugpsrk9a.css';
import '../../css/o/ob15v7gie.css';
import '../../css/x/x__he7ltf.css';
import '../../css/f/fjt70sb3a.css';
import '../../css/v/v9m8k33eh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pugpsrk9a"/><path class="ob15v7gie wm-k"/><path class="wm-a x__he7ltf"/><path class="fjt70sb3a wm-k"/><path class="v9m8k33eh wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:air-vent-sketch" {...props}></Icon>
