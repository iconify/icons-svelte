<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/x5p80bb3e.css';
import '../../css/x/xnjzunbdq.css';
import '../../css/c/c63s6_bnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="x5p80bb3e"/><path class="xnjzunbdq"/><path class="c63s6_bnf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:layer-boxes" {...props}></Icon>
