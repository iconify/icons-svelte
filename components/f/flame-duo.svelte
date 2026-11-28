<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frtq6fbtd.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/fwi20wbqk.css';
import '../../css/l/l177jbcau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frtq6fbtd secondary"/><g class="dt0cm9dhy primary"><path class="fwi20wbqk"/><path class="l177jbcau"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flame-duo" {...props}></Icon>
