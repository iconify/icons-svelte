<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb_wbthuz.css';
import '../../css/q/qtkf3h-or.css';
import '../../css/a/ai3a9kmls.css';
import '../../css/g/g5rjs7bks.css';
import '../../css/y/yy60akbdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tb_wbthuz"/><path class="qtkf3h-or"/><circle class="ai3a9kmls"/><circle class="g5rjs7bks"/><path class="yy60akbdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:faxicon" {...props}></Icon>
