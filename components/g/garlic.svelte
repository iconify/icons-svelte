<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm3ivccum.css';
import '../../css/b/bg8astbrt.css';
import '../../css/b/bwy4czm5u.css';
import '../../css/g/g3jivrnhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="vm3ivccum"><path class="bg8astbrt"/><path class="bwy4czm5u"/><path class="g3jivrnhg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:garlic" {...props}></Icon>
