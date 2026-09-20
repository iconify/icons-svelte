<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/c/cqclfwlbl.css';
import '../../css/q/qtwmcobht.css';
import '../../css/p/p9ze6rn7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path vector-effect="non-scaling-stroke" class="cqclfwlbl"/><path class="qtwmcobht"/><path vector-effect="non-scaling-stroke" class="p9ze6rn7i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:playlist-track" {...props}></Icon>
