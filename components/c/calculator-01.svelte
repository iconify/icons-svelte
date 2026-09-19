<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/f56xg1bhf.css';
import '../../css/s/swod1gpfm.css';
import '../../css/z/z1g_9wh2e.css';
import '../../css/k/k7lkoqbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="f56xg1bhf"/><path class="swod1gpfm"/><path class="z1g_9wh2e"/><path class="k7lkoqbhp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:calculator-01" {...props}></Icon>
