<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvwfwbb0g.css';
import '../../css/p/ptkyfbcbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvwfwbb0g"/><path class="ptkyfbcbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-group" {...props}></Icon>
