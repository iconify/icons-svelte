<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/b/b51-lhp3z.css';
import '../../css/s/se2qxethe.css';
import '../../css/g/gp4pu0sxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><rect class="b51-lhp3z"/><path class="se2qxethe"/><path class="gp4pu0sxh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:nine-key" {...props}></Icon>
