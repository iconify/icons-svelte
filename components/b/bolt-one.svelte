<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/g/gtr29ujph.css';
import '../../css/m/mg2vvdbge.css';
import '../../css/e/eb8fy6btr.css';
import '../../css/b/b0fz9dbol.css';
import '../../css/v/vfj5kp_5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="gtr29ujph"/><path class="mg2vvdbge"/><path class="eb8fy6btr"/><path class="b0fz9dbol"/><path class="vfj5kp_5t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:bolt-one" {...props}></Icon>
