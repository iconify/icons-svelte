<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jijxp98_q.css';
import '../../css/t/t8j_1ujbr.css';
import '../../css/c/cq1ipmmsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="jijxp98_q"/><path class="t8j_1ujbr"/><path class="cq1ipmmsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-mail-unread" {...props}></Icon>
