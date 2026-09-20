<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/ar3kukqib.css';
import '../../css/g/gfak_b84w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ar3kukqib"/><path class="gfak_b84w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:flow-tree-duotone" {...props}></Icon>
