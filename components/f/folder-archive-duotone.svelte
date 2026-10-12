<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tsfpps3-a.css';
import '../../css/j/jcl7bgvzi.css';
import '../../css/w/w1g0myb6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tsfpps3-a"/><path class="jcl7bgvzi"/><path class="w1g0myb6g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:folder-archive-duotone" {...props}></Icon>
