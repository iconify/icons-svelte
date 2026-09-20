<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wruywg-vy.css';
import '../../css/b/bvjck1u0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wruywg-vy"/><path class="bvjck1u0k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:play-previous-duotone" {...props}></Icon>
