<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/o/otc11ybpz.css';
import '../../css/q/qx4gc400j.css';
import '../../css/f/fr15c8b3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="otc11ybpz"/><path class="qx4gc400j"/><path class="fr15c8b3o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mouse-05" {...props}></Icon>
