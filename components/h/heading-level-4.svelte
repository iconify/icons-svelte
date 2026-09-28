<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/jb730ab3d.css';
import '../../css/g/g9av7kz0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path vector-effect="non-scaling-stroke" class="jb730ab3d"/><path vector-effect="non-scaling-stroke" class="g9av7kz0z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:heading-level-4" {...props}></Icon>
