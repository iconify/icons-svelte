<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/binn1sb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="binn1sb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:fold-horizontal-dashed" {...props}></Icon>
