<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pumb42b6l.css';
import '../../css/y/yl3hz14bt.css';
import '../../css/x/xmntywhuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pumb42b6l"/><circle class="yl3hz14bt"/><path class="xmntywhuu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:photo-multiple" {...props}></Icon>
