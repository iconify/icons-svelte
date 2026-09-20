<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/l/l3i4eqbnf.css';
import '../../css/k/k59f9ebtr.css';
import '../../css/n/nmc1rlb0c.css';
import '../../css/m/mw2wcobik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="l3i4eqbnf"/><path class="k59f9ebtr"/><circle class="nmc1rlb0c"/><path class="mw2wcobik"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:chat-search-light" {...props}></Icon>
