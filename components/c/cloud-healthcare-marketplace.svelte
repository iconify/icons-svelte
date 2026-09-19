<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/t/tcvz_bb_s.css';
import '../../css/c/cfc7gmban.css';
import '../../css/x/x2j6x9bwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="bi12bsetm"><path class="tcvz_bb_s"/><path class="cfc7gmban"/><path class="x2j6x9bwh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:cloud-healthcare-marketplace" {...props}></Icon>
