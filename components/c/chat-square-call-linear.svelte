<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/o9dmu8blt.css';
import '../../css/g/grb0q__0e.css';
import '../../css/l/lyi2etljr.css';
import '../../css/e/eq3frqb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="o9dmu8blt"/><path class="grb0q__0e"/><path class="lyi2etljr"/><path class="eq3frqb0l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-call-linear" {...props}></Icon>
