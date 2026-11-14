<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/u7zizkbrr.css';
import '../../css/d/df-j23bjo.css';
import '../../css/j/jkp3rmbnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="u7zizkbrr"/><path class="df-j23bjo"/><path class="jkp3rmbnz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mail-reply-02" {...props}></Icon>
