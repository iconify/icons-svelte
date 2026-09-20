<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/yejbj_b4f.css';
import '../../css/c/cay-wqb7i.css';
import '../../css/r/rxe-uvbkx.css';
import '../../css/r/r9flb0bga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="yejbj_b4f"/><path class="cay-wqb7i"/><path class="rxe-uvbkx"/><path class="r9flb0bga"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:notification-bell-upload" {...props}></Icon>
