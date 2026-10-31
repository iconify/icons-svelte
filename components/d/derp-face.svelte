<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mtdee3zsb.css';
import '../../css/f/fnj4pjb-k.css';
import '../../css/d/d3ldqpb6o.css';
import '../../css/b/b91ed8jnd.css';
import '../../css/y/yeckeacte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="mtdee3zsb"/><circle class="fnj4pjb-k"/><circle class="d3ldqpb6o"/><path class="b91ed8jnd"/><path clip-rule="evenodd" class="yeckeacte"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-memes:derp-face" {...props}></Icon>
