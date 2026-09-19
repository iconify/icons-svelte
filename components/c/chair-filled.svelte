<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d28nq_1xp.css';
import '../../css/m/mwlmu5b9e.css';
import '../../css/w/w49j0rbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGmDobbeyg"><path clip-rule="evenodd" class="d28nq_1xp"/><path class="mwlmu5b9e"/></mask></defs><path mask="url(#SVGmDobbeyg)" class="w49j0rbvv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:chair-filled" {...props}></Icon>
