<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/k/kgpwylbgu.css';
import '../../css/i/i7dhmn0vg.css';
import '../../css/o/of67m-bqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="kgpwylbgu"/><path class="i7dhmn0vg"/><path class="of67m-bqt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:chart-rose" {...props}></Icon>
