<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/e/ecude2y5f.css';
import '../../css/j/jvtjbnueh.css';
import '../../css/p/pn0k_1bgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ecude2y5f"/><path class="jvtjbnueh"/><path class="pn0k_1bgo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:maps-square-01" {...props}></Icon>
