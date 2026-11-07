<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/paayxvxde.css';
import '../../css/l/li3xrhb9c.css';
import '../../css/d/dmzio9b4p.css';
import '../../css/r/rw8hl94tg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="paayxvxde"/><path class="li3xrhb9c"/><path class="dmzio9b4p"/><path class="rw8hl94tg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:book-bookmark-minimalistic-broken" {...props}></Icon>
