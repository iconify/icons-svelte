<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/j/jexdvubgo.css';
import '../../css/b/b9h-f8bxl.css';
import '../../css/v/vb28crb_k.css';
import '../../css/g/g5e8xw6vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="jexdvubgo"/><path class="b9h-f8bxl"/><path class="vb28crb_k"/><path class="g5e8xw6vn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:folder-close" {...props}></Icon>
