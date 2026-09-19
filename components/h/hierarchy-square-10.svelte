<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/fyq5n8b7t.css';
import '../../css/x/xtfl08bxn.css';
import '../../css/a/aqxq3ddkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="fyq5n8b7t"/><path class="xtfl08bxn"/><path class="aqxq3ddkl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:hierarchy-square-10" {...props}></Icon>
