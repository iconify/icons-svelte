<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/rcsj_abfu.css';
import '../../css/z/zg5fcjbls.css';
import '../../css/v/v4a1nrb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="rcsj_abfu"/><path class="zg5fcjbls"/><path class="v4a1nrb3e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mouse-20" {...props}></Icon>
