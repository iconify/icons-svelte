<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbey_ib_d.css';
import '../../css/w/wid62-bcc.css';
import '../../css/b/brzn_0bpr.css';
import '../../css/u/u1gdy3bvt.css';
import '../../css/y/y96dlxsxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="pbey_ib_d"/><path class="wid62-bcc"/><g class="brzn_0bpr"><path class="u1gdy3bvt"/><path class="y96dlxsxv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:cup-with-straw" {...props}></Icon>
