<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/j/jhpso8b8b.css';
import '../../css/n/np1e_hbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jhpso8b8b"/><circle transform="matrix(-1 0 0 1 8 3)" class="np1e_hbeg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bounce-left" {...props}></Icon>
