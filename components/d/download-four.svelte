<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm3ivccum.css';
import '../../css/x/xsa7a0bbn.css';
import '../../css/q/qvra_uwad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="vm3ivccum"><path clip-rule="evenodd" class="xsa7a0bbn"/><path class="qvra_uwad"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:download-four" {...props}></Icon>
