<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jw2qqyvrp.css';
import '../../css/k/kuweadcxn.css';
import '../../css/a/au3i8qbhp.css';
import '../../css/b/bfb60nbvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="jw2qqyvrp"/><path class="kuweadcxn"/><path class="au3i8qbhp"/><path class="bfb60nbvk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:knife-fork" {...props}></Icon>
