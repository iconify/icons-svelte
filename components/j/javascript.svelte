<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn9lnnxdg.css';
import '../../css/s/sxsjrzbyv.css';
import '../../css/m/mpei81s8z.css';
import '../../css/v/v41lcbbao.css';
import '../../css/f/favxc-rsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="sn9lnnxdg"/><g class="sxsjrzbyv"><path class="mpei81s8z"/><path clip-rule="evenodd" class="v41lcbbao"/><path clip-rule="evenodd" class="favxc-rsv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:javascript" {...props}></Icon>
