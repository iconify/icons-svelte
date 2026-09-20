<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/w/wewio4b2f.css';
import '../../css/c/c8tqhzbrd.css';
import '../../css/t/ttdmdibgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wewio4b2f"/><path class="c8tqhzbrd"/><path class="ttdmdibgv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:fish-off" {...props}></Icon>
