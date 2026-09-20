<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/q/qihxq122b.css';
import '../../css/x/x66xuvg5w.css';
import '../../css/l/lm2y_hbzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="qihxq122b"/><path class="x66xuvg5w"/><circle class="lm2y_hbzh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:inbox-notification" {...props}></Icon>
