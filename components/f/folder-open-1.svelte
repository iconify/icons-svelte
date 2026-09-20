<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bi8tgtb-z.css';
import '../../css/d/dpqwqi72y.css';
import '../../css/s/si341hb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bi8tgtb-z"/><path class="dpqwqi72y"/><path class="si341hb2m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:folder-open-1" {...props}></Icon>
