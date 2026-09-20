<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d7xy4dvdq.css';
import '../../css/o/o3g4sn7py.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d7xy4dvdq"/><path clip-rule="evenodd" class="o3g4sn7py"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:car" {...props}></Icon>
