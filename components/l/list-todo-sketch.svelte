<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/s5lv8gbfq.css';
import '../../css/g/g2knpnl4g.css';
import '../../css/e/ecoxr8ars.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="s5lv8gbfq wm-k"/><path class="g2knpnl4g wm-a"/><path class="ecoxr8ars wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:list-todo-sketch" {...props}></Icon>
