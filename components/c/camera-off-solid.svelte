<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h7dpe5z2n.css';
import '../../css/g/gmstibmbn.css';
import '../../css/f/fr8h0cc5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="h7dpe5z2n wm-k"/><circle class="gmstibmbn wm-a"/><path class="fr8h0cc5s wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:camera-off-solid" {...props}></Icon>
