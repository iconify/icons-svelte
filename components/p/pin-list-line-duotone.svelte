<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/tmz3cbcrl.css';
import '../../css/y/yfu3bb1vx.css';
import '../../css/x/xyk6mx0ds.css';
import '../../css/b/bfhdazbsl.css';
import '../../css/z/zfc5svshd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tmz3cbcrl"/><path class="yfu3bb1vx"/><path class="xyk6mx0ds"/><path class="bfhdazbsl"/><path class="zfc5svshd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pin-list-line-duotone" {...props}></Icon>
