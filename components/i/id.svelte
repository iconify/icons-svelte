<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/k/k83jpvbjp.css';
import '../../css/x/x5rt7xbfv.css';
import '../../css/p/p9j8izb5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="k83jpvbjp"/><path class="x5rt7xbfv"/><path class="p9j8izb5f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:id" {...props}></Icon>
