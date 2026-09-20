<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srpby-b4v.css';
import '../../css/e/effr8obxp.css';
import '../../css/m/m3ckqtbim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="srpby-b4v"/><path class="effr8obxp"/><path class="m3ckqtbim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:diffs-rtl" {...props}></Icon>
