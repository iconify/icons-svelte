<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qeh60pb0k.css';
import '../../css/s/smjp0hbny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qeh60pb0k"/><path class="smjp0hbny"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:castle-alt-1-duotone" {...props}></Icon>
