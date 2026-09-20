<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd2af0bmx.css';
import '../../css/e/e5_g43bxn.css';
import '../../css/t/t56zhebui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="qd2af0bmx"/><path class="e5_g43bxn"/><path class="t56zhebui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:cooked-rice" {...props}></Icon>
